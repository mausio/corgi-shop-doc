# Software Architecture Document #

# 1. Einleitung

Die Corgi-Shop-App wurde entwickelt, um eine effiziente Plattform für den Verkauf von Corgis und exklusivem Corti-Merchandise zu bieten. Technologisch fortgeschritten, verfolgt die Anwendung das Ziel, hochwertige Produkte effizient zu verkaufen und gleichzeitig ein reibungsloses Einkaufserlebnis für die Benutzer zu gewährleisten.

Die technische Umsetzung umfasst fortschrittliche E-Commerce-Technologien, die eine nahtlose Navigation und Interaktion ermöglichen. Der Fokus liegt auf einer agilen Backend-Architektur, die eine schnelle Verarbeitung von Transaktionen und die effiziente Verwaltung von Produktdaten gewährleistet.

Durch den Einsatz modernster Technologien für Datenmanagement und E-Commerce strebt die Corgi-Shop-App nicht nur an, hochwertige Produkte anzubieten, sondern auch eine robuste und sichere Plattform für den Verkauf von Corgis und Corti-Merchandise bereitzustellen.

# 2. Architektonische Darstellung

Die Corgi-Shop-App ist durch eine durchdachte Architektur geprägt, die auf Swift im Frontend, Java SpringBoot im Backend und PostgreSQL als Datenbank setzt. Swift sorgt für eine optimale Benutzererfahrung auf iPhones, während SpringBoot eine skalierbare und robuste Serverarchitektur gewährleistet. Die PostgreSQL-Datenbank speichert effizient Produktdaten, Benutzerinformationen und Bestellungen.

Die Kommunikation zwischen den Komponenten erfolgt über RESTful APIs, die eine klare Trennung der Verantwortlichkeiten ermöglichen. Eine zusätzliche Sicherheitsschicht schützt Benutzerdaten durch bewährte Mechanismen wie Authentifizierung und Autorisierung.

![AD](https://github.com/mausio/corgi-shop-doc/assets/115564658/ec2c3c28-82be-4f5b-ac38-e22ca869035f)

# 3. Architektonische Ziele und Einschränkungen

In architektonischer Hinsicht liegt der Fokus auf der Benutzerfreundlichkeit, wobei die Anwendung mit Swift im Frontend, Java SpringBoot im Backend und einer PostgreSQL-Datenbank entwickelt wurde. 
Die Anwendung wird ausschließlich auf dem iPhone betriebent.

Sicherheits- und Datenschutzanforderungen wurden nicht spezifiziert, aber es wurden grundlegende Sicherheitspraktiken implementiert. 
Die Anwendung strebt eine akzeptable Leistung an, und obwohl Skalierbarkeit nicht explizit genannt wurde, wird erwartet, dass die Anwendung insgesamt zuverlässig ist.

Insgesamt wird die Architektur darauf ausgerichtet, eine effiziente und benutzerfreundliche Plattform für den exklusiven Kauf von Corgi-Produkten auf mobilen Apple-Geräten zu bieten.

# 4. Anwendungsfall-Ansicht

Zwei der Anwendungsfälle sind in unseren UCRS beschrieben:

[Corgi-Tabelle](https://github.com/mausio/corgi-shop-doc/blob/main/ucrs/ucrs-1-CorgiTab.md)
[User-Login](https://github.com/mausio/corgi-shop-doc/blob/main/ucrs/ucrs-2-User-Login.md)

# 5. Logische Ansicht

Das Klassendiagramm visualisiert alle Klassen sowie dessen Attribute, Methoden und deren Relationen im BackEnd.

![Klassendiagramm](https://github.com/mausio/corgi-shop-doc/blob/main/classdiagram/cd2.drawio.png)

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

Die Datenbank und das Backend müssen jederzeit verfügbar sein. Die Antwortzeiten müssen in einem Bereich liegen, um die Benutzerinteraktion nicht zu beeinträchtigen. Beide müssen für zukünftige Funktionen erweiterbar sein. Die Leistung des Backends kann die Gesamtantwortzeiten am stärksten beeinflussen, daher sind Optimierungen hier entscheidend.

Das Frontend sollte ebenfalls erweiterbar sein, um die Funktionen des Backends zu spiegeln. Die Leistung muss sehr gut sein, da der Benutzer direkt damit interagiert.

# 11. Qualität

Die Anwendung gewährleistet zuverlässiges Anzeigen von Produkten und das Hinzufügen zu Favoriten ohne Unterbrechungen. 
Die Favoritenfunktion ermöglicht es Nutzern, Produkte bequem zu speichern und später wiederzufinden.

Um kurze Ladezeiten zu gewährleisten, werden GUI-Komponenten optimiert, und Daten aus dem Backend werden effizient geladen, um eine flüssige Nutzung sicherzustellen.

Die Sicherheit sensibler Kundendaten wird durch eine sichere Anmeldung mittels E-Mail und Passwort gewährleistet. Alle Übertragungen erfolgen verschlüsselt.

Die Architektur der Anwendung ist darauf ausgerichtet, auf eine wachsende Benutzerzahl zu reagieren und eine konsistente Dienstleistungsqualität sicherzustellen.

Diese Qualitätsmerkmale werden während des gesamten Entwicklungsprozesses überwacht, um sicherzustellen, 
dass die Corgi-Shop-Anwendung den höchsten Standards entspricht und eine erstklassige Benutzererfahrung auf dem iPhone bietet.

