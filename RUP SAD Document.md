# Software Architecture Document #

# 1. Einleitung
## 1.1 Zweck
## 1.2 Umfang
## 1.3 Definitionen, Akronyme und Abkürzungen
## 1.4 Referenzen
## 1.5 Überblick

# 2. Architektonische Darstellung

# 3. Architektonische Ziele und Einschränkungen

In architektonischer Hinsicht liegt der Fokus auf der Benutzerfreundlichkeit, wobei die Anwendung mit Swift im Frontend, Java SpringBoot im Backend und einer PostgreSQL-Datenbank entwickelt wurde. 
Die Anwendung wird ausschließlich auf dem iPhone betriebent.

Sicherheits- und Datenschutzanforderungen wurden nicht spezifiziert, aber es wurden grundlegende Sicherheitspraktiken implementiert. 
Die Anwendung strebt eine akzeptable Leistung an, und obwohl Skalierbarkeit nicht explizit genannt wurde, wird erwartet, dass die Anwendung insgesamt zuverlässig ist.

Insgesamt wird die Architektur darauf ausgerichtet, eine effiziente und benutzerfreundliche Plattform für den exklusiven Kauf von Corgi-Produkten auf mobilen Apple-Geräten zu bieten.

# 4. Anwendungsfall-Ansicht
## 4.1 Realisierungen von Anwendungsfällen

# 5. Logische Ansicht
## 5.1 Überblick
## 5.2 Architektonisch signifikante Designpakete

# 6. Prozessansicht

![sqd_4 drawio](https://github.com/mausio/corgi-shop-doc/assets/122524882/e48f0105-1bd5-4912-8f99-61b5dcc6eb15)

Das Sequenzdiagramm zeigt aktuell wie die App die Corgis aus der Datenbank zieht und anzeigt.
Es wird aktualisiert sobald weiteres vollständig implementiert wurde.

# 7. Bereitstellungsansicht

# 8. Implementierungsansicht

## 8.1 Überblick

Während das Frontend nur die GUI-Komponente besitzt und Services für die Logik, so besitzt das Backend die Restcontroller, Services, DAO's und DTO's. Das Backend kommuniziert über die DAO's mit der Datenbank.

## 8.2 Schichten

![KD_1 drawio](https://github.com/mausio/corgi-shop-doc/assets/115564658/7a6c933a-a0aa-4574-937f-e431d426810f)

# 9. Datenansicht (optional)

# 10. Größe und Leistung

# 11. Qualität

Die Anwendung gewährleistet zuverlässiges Anzeigen von Produkten und das Hinzufügen zu Favoriten ohne Unterbrechungen. 
Die Favoritenfunktion ermöglicht es Nutzern, Produkte bequem zu speichern und später wiederzufinden.

Um kurze Ladezeiten zu gewährleisten, werden GUI-Komponenten optimiert, und Daten aus dem Backend werden effizient geladen, um eine flüssige Nutzung sicherzustellen.

Die Sicherheit sensibler Kundendaten wird durch eine sichere Anmeldung mittels E-Mail und Passwort gewährleistet. Alle Übertragungen erfolgen verschlüsselt.

Die Architektur der Anwendung ist darauf ausgerichtet, auf eine wachsende Benutzerzahl zu reagieren und eine konsistente Dienstleistungsqualität sicherzustellen.

Diese Qualitätsmerkmale werden während des gesamten Entwicklungsprozesses überwacht, um sicherzustellen, 
dass die Corgi-Shop-Anwendung den höchsten Standards entspricht und eine erstklassige Benutzererfahrung auf dem iPhone bietet.

