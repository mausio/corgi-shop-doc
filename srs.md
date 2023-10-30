# Software Requirement Specifications (SRS)

## Beschreibung

Das SRS Document beschreibt alle Spezifikationen im Rahmen des Projekts „Corgi-Shop“ und gibt einen Überblick über die Zukunft des Projekts, was die Features und die Begrenzungen inkludiert.

## Scope

Folgende Funktionalitäten realisiert die App:
1.	Corgis
      - Corgis aus Back End fetchen und im Front End als Liste darstellen
      - Einzelnen Corgi darstellen und Informationen darstellen
      - Corgis als Favorit speicherbar machen
      - Corgi in den Einkaufskorb einchecken
2.	Merch
3.	Home / Gesamtüberblick
4.	Checkout
5.	Profil
6.	Admin

## Verwendete Tech-Stacks:

- Backend:
Java
Spring Boot
PostgresSQL (TablePlus)

- Frontend:
Swift (UI)
iOS Kits
SwiftData

- IDE:
IntelliJ Ultimate
Xcode

- Projektmanagement:
Jira (Atlassian)
Github Docs / Discussions

- Deployment:
Docker

- Testing:
JUnit

## GUI-Mock-Up (Profil/User)

<img width="326" alt="Screenshot_2023-10-30_at_11 36 38" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/4283b343-cbdc-442f-9b5c-ae40a891db27">
<img width="326" alt="Screenshot_2023-10-30_at_11 36 43" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/f8f03db9-143a-428a-b439-bd6680693d1c">

Das GUI-Mock-Up stellt das zukünftige Graphical User Interface der App dar.
Das erste Bild zeigt wie die Corgis im Katalog und das zweite wie die Seiten individueller Corgis in der App jeweils angezeigt werden sollen.

## Use-Case-Diagramm

![ucd1](https://github.com/mausio/corgi-shop-doc/assets/122524882/3a5d41ba-8358-4f5e-aacd-e3df6feb296a)


Das Use-Case-Diagramm illustriert die verschiedenen Anwendungsmöglichkeiten der Corgi-Shop-App. 
Kunden sollen die Möglichkeit haben, sich einzuloggen, Corgis oder Merchandise-Produkte anzusehen, diese zu kaufen oder den Bezahlvorgang zu starten. 
Das Log-In sowie das Checkout und das Kaufen von Produkten wird zuerst über das Back-End verarbeitet und gegebenenfalls werden mit der Datenbank Daten ausgetauscht. 
Der Bezahlvorgang selbst wird von den Payment Services über das Back-End verwaltet.

## Sequenzdiagramm

<img width="524" alt="Bildschirmfoto_2023-10-30_um_12 28 48" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/1cf9d637-ea4e-4214-ad82-7a8d009f439a">

Das Sequenzdiagramm zeigt aktuell wie die App die Corgis aus dem der Datenbank holt und sie anzeigt.
Es wird aktualisiert sobald weiteres vollständig implementiert wurde
