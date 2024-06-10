# Handout zur Präsentation "Corgi Shop"

Dieses Handout enthält die wichtigsten Informationen für die Präsentation "Corgi Shop". Dazu gehören folgende Informationen:

- Projektname
- Aufwändsstatistik
- Highlights der Demo
- Architektur
- Software-Tools/Plattform/Technologie/Bibliotheken
- Datenbank und Design
- Testen
- Metriken
- CI/CD

## Projektname

Als Projektname wurde "Corgi Shop" gewählt.

## Aufwändsstatistik

Das Projektteam besteht aus folgenden Mitgliedern:

- Mael Dossoh: BackEnd, Testen, CI/CD, Dokumentation
- Niklas Krauth: BackEnd, Datenbank, Dokumentation
- Robin Schwenzfeier: FrontEnd, Teamleiter

### Commits
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Doku</th>
      <th>BackEnd</th>
      <th>FrontEnd</th>
      <th>Gesamtzahl Commits</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Mael Dossoh</td>
      <td>26</td>
      <td>11</td>
      <td>0</td>
      <td>37</td>
    </tr>
    <tr>
      <td>Niklas Krauth</td>
      <td>17</td>
      <td>22</td>
      <td>0</td>
      <td>39</td>
    </tr> 
    <tr>
      <td>Robin Schwenzfeier</td>
      <td>14</td>
      <td>3</td>
      <td>17</td>
      <td>34</td>
    </tr>
  </tbody>
</table>

### Stunden

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Beschreibung</th>
      <th>Niklas</th>
      <th>Mael</th>
      <th>Robin</th>
      <th>Gesamt</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Corgis Front-/BackEnd (Sprint)</td>
      <td>iOS App; Swift und SwiftData; API Anbindung (REST) und Statemangement; Styling/Endpoints; Datenbankanbindung; End-to-End Testing (Postman)</td>
      <td>25</td>
      <td>5</td>
      <td>65</td>
      <td>95</td>
    </tr>
    <tr>
      <td>Merch Front-/BackEnd (Sprint)</td>
      <td>iOS App; Swift und SwiftData; API Anbindung (REST) und Statemangement; Styling/Endpoints; Datenbankanbindung; End-to-End Testing (Postman)</td>
      <td>15</td>
      <td>18</td>
      <td>5</td>
      <td>38</td>
    </tr>
     <tr>
      <td>User Front-/BackEnd (Sprint)</td>
      <td>iOS App; Swift und SwiftData; API Anbindung (REST) und Statemangement; Styling/Endpoints; Datenbankanbindung; End-to-End Testing (Postman)</td>
      <td>13</td>
      <td>9</td>
      <td>4</td>
      <td>26</td>
    </tr>
     <tr>
      <td>Cart Front-/BackEnd (Sprint)</td>
      <td>iOS App; Swift und SwiftData; API Anbindung (REST) und Statemangement; Styling/Endpoints; Datenbankanbindung; End-to-End Testing (Postman)</td>
      <td>5</td>
      <td>5</td>
      <td>3</td>
      <td>13</td>
    </tr>
    <tr>
      <td>Sprint Planung (Dokumentation)</td>
      <td>Planung, Einträge und Workflow verfolgen auf Jira</td>
      <td>8</td>
      <td>8</td>
      <td>8</td>
      <td>24</td>
    </tr>
    <tr>
      <td>SRS (Dokumentation)</td>
      <td>Projektplanung und Festsetzung der Vision und Konkretisierung der Umsetzung der Applikation</td>
      <td>5</td>
      <td>10</td>
      <td>2</td>
      <td>17</td>
    </tr>
    <tr>
      <td>Klassendiagramme (Dokumentation)</td>
      <td>Erfassen, Analyse und Visualisierung der Klassen, der Beziehungen und Versionierung</td>
      <td>12</td>
      <td>0</td>
      <td>2</td>
      <td>14</td>
    </tr>
    <tr>
      <td>Use Case/User Story (Dokumentation)</td>
      <td>Nutzerverhalten und Bedienbarkeit der App durch Definition der Abläufe</td>
      <td>0</td>
      <td>5</td>
      <td>5</td>
      <td>10</td>
    </tr>
    <tr>
      <td>ASR (Dokumentation)</td>
      <td>Diskussion und Festlegung der Architektur und Entscheidung</td>
      <td>0</td>
      <td>5</td>
      <td>0</td>
      <td>5</td>
    </tr>
    <tr>
      <td>RUP SAD (Dokumentation)</td>
      <td>Dokumentation für bestehende Architektur und spezifische Implementierung</td>
      <td>5</td>
      <td>0</td>
      <td>0</td>
      <td>5</td>
    </tr>
    <tr>
      <td>RMMM (Dokumentation)</td>
      <td>Erfassung von Risiken, Bewältigungstrategien und Erstellung von Visualisierungen/td>
      <td>0</td>
      <td>5</td>
      <td>0</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Clean Code(Dokumentation)</td>
      <td>Zusammenstellung der verwendeten Clean Code Techniken</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Testen Front-/BackEnd (Sprint & Dokumentation)</td>
      <td>Durchführung und Dokumentation von Front-/BackEnd-Tests </td>
      <td>0</td>
      <td>5</td>
      <td>5</td>
      <td>10</td>
    </tr>
    <tr>
      <td>CI/CD (Sprint & Dokumentation)</td>
      <td>Implementierung sowie Dokumentation einer Pull Request CI/CD Pipeline </td>
      <td>0</td>
      <td>8</td>
      <td>0</td>
      <td>8</td>
    </tr>
    <tr>
      <td>Presentationen & Handouts (Dokumentation)</td>
      <td>Erstellen der beiden Dokumenten für das jeweilige Semester</td>
      <td>0</td>
      <td>6</td>
      <td>6</td>
      <td>12</td>
    </tr>
    <tr>
      <td>Planung, Kommunikation(Dokumentation)</td>
      <td>Zeitaufwand für Planung, Kommunikation, Koordination</td>
      <td>4</td>
      <td>4</td>
      <td>13</td>
      <td>21</td>
    </tr>
    <tr>
      <td>Zusammenfassung</td>
      <td>Stunden pro Person</td>
      <td>= 99</td>
      <td>= 93</td>
      <td>= 120</td>
      <td>= 312</td>
    </tr>
  </tbody>
</table>


## Hauptbeiträge jedes Teammitglieds (in eigenen Worten)
Hier werden in wenigen eigenen Worten von den Teammitgliedern die Hauptbeiträge selbst beschrieben.

#### Robin Schwenzfeier
Ich habe mich ausschließlich um das FrontEnd gekümmert, die Aufgaben verteilt, die Qualitätssicherung übernommen und Teile der Dokumentation übernommen.
Im BackEnd kam noch Code Review hinzu und Feedback durch die entstehende Nutzung im FrontEnd.
Versionierung und Organisation der Dokumentation, sowie die Kommunikation und Terminplanung habe ich ebenfalls übernommen.

####  Mael Dossoh
Hauptsächlich habe ich mich um die Dokumentation des Projekts gekümmert, einschließlich der Erstellung des SRS, ASR und RMMM.
Auußerden habe ich die Merch- und Cart-Endpunkte der Datenbank angelegt und mich die Verbindung zum Frontend sowie das Testing und CI/CD gekümmert.

#### Niklas Krauth
Größtenteils habe ich mich um das BackEnd gekümmert welches ich erstellt habe sowie die grundlegende Architektur und die Corgi-Endpunkte dort. 
Auch habe ich mich um die Datenbank gekümmert. Dazu wurden auch die meisten Diagramme von mir erstellt.

## Architektur - [Zum Blogeintrag](https://github.com/mausio/corgi-shop-doc/discussions/4)
Das Blogbeitrag geht ausführlicher auf die Architektur ein, jedoch, im Kurzen, ist die Architektur wie folgt aufgebaut:
- FrontEnd: Swift, SwiftUI und SwiftData bilden den View und Teile vom Controller (Actions, die dispatched werden) und beziehen Daten bei Bedarf vom BackEnd.
- BackEnd: Spring Boot, Java und MySQL bilden das Model und den Controller und stellen die Daten für das FrontEnd bereit.

## Software Tools/Plattform/Technik/Libraries
Genutzte Tech Stacks:

### BackEnd

- Spring Boot
- Java
- JUnit
- PostgreSQL
- Postman
- TablePlus
- IntelliJ IDEA
- Git
- Github
- Github Actions
- Docker

### FrontEnd

- Xcode
- Swift 
- iOS
- Spring Boot (BackEnd als REST API)
- Git
- Github

## Datenbank und Design - [Zum Blogeintrag](https://github.com/mausio/corgi-shop-doc/discussions/6)

### Struktur
Die Datenbank für "Corgi Shop" wurde mit PostgreSQL implementiert. Die Haupttabellen umfassen:

- Users: Enthält Informationen zu den Nutzern (ID, Name, E-Mail, Passwort, etc.)
- Corgis: Enthält Informatoonen zu den Corgis (ID, Name, Preis, etc.)
- Items: Speichert Produktinformationen (ID, Name, Beschreibung, Preis, etc.)
- Cart: Verfolgt die Artikel im Warenkorb der Benutzer (ID, Benutzer-ID, Produkt-ID, Menge, etc.)

### 1Design
Das Datenbankdesign folgt dem Prinzip der Normalisierung bis zur dritten Normalform (3NF), um Redundanz zu minimieren und Datenkonsistenz zu gewährleisten.

ER-Diagramm
Das Entity-Relationship-Diagramm (ERD) zeigt die Beziehungen zwischen den verschiedenen Entitäten der Datenbank. Die Hauptbeziehungen sind:
Ein Benutzer kann mehrere Bestellungen haben.
Ein Produkt kann in mehreren Bestellungen enthalten sein.
Ein Benutzer kann mehrere Produkte in seinem Warenkorb haben.

## Testing - Zu den Blockeinträgen: [FrontEnd-Testing](https://github.com/mausio/corgi-shop-doc/discussions/14), [BackEnd-Testing](https://github.com/mausio/corgi-shop-doc/discussions/15)

### Unit Testing
Für das Unit Testing wurde JUnit verwendet. Alle kritischen Funktionalitäten im Backend wurden durch Unit Tests abgedeckt, um sicherzustellen, dass jede einzelne Komponente wie erwartet funktioniert.

### Integration Testing
Integrationstests wurden durchgeführt, um sicherzustellen, dass verschiedene Bestandteile des Systems nahtlos zusammenarbeiten. Postman wurde verwendet, um API-Endpunkte zu testen und sicherzustellen, dass sie korrekt funktionieren.

### End-to-End Testing
End-to-End-Tests wurden mit Postman durchgeführt, um den gesamten Workflow vom Frontend bis zum Backend zu überprüfen. Diese Tests stellten sicher, dass Benutzeraktionen ordnungsgemäß verarbeitet und in der Datenbank korrekt gespeichert wurden.

## Metriken - [Zum Blogeintrag](https://github.com/mausio/corgi-shop-doc/discussions/16)

### Code Coverage
Die Code Coverage wurde mithilfe von JaCoCo gemessen, um sicherzustellen, dass mindestens 80% des Codes durch Tests abgedeckt sind.

### Performance Metrics
Die Performance der Anwendung wurde mit JMeter getestet. Die Hauptkennzahlen umfassen:

Durchschnittliche Antwortzeit: Zeit, die das System benötigt, um auf eine Anfrage zu antworten.
Durchsatz: Anzahl der Anfragen, die das System pro Sekunde verarbeiten kann.
Fehlerrate: Prozentsatz der fehlgeschlagenen Anfragen im Vergleich zur Gesamtzahl der Anfragen.

## CI/CD - [Zum Blogeintrag](https://github.com/mausio/corgi-shop-doc/discussions/18)

### Continuous Integration (CI)
Die Continuous Integration wurde mit GitHub Actions implementiert. Bei jedem Pull Request werden automatisch Build- und Testprozesse gestartet. Dies gewährleistet, dass neue Änderungen keine bestehenden Funktionalitäten brechen.

### Continuous Deployment (CD)
Das Continuous Deployment wird ebenfalls mit GitHub Actions durchgeführt. Nach erfolgreichem Durchlaufen der CI-Pipeline wird der Code automatisch in die Produktionsumgebung bereitgestellt. Docker wird verwendet, um die Anwendung in Container zu verpacken und zu deployen.

### CI/CD Pipeline
Die CI/CD-Pipeline umfasst folgende Schritte:

Code-Checkout: Abrufen des neuesten Codes aus dem Git-Repository.
Build: Kompilieren und Erstellen der Anwendung.
Test: Ausführen aller Unit-, Integrations- und End-to-End-Tests.
Deploy: Bereitstellen der Anwendung in der Produktionsumgebung.
