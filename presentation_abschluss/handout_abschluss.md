# Handout zur Präsentation "Corgi Shop"

Dieses Handout enthält die wichtigsten Informationen zur Präsentation "Corgi Shop". Dazu gehören folgende Informationen:

- Projektnamen
- Aufwändsstatistiken
- Highlights der Demo
- Architektur
- Software Tools/Plattform/Technik/Libraries
- Datenbank und Design
- Testing
- Metriken
- CI/CD

## Projektnamen

Der gewählte Projektnamen lautet "Corgi Shop".

## Aufwändsstatistiken

Das Projektteam besteht aus folgenden Mitgliedern:

- Mael Dossoh: BackEnd, Testing, CI/CD, Dokumentation
- Niklas Krauth: BackEnd, Database, Migration
- Robin Schwenzfeier: FrontEnd, Teamleader

### Commits
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Doku</th>
      <th>BackEnd</th>
      <th>FrontEnd</th>
      <th>Gesamt Anzahl Commits</th>
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
      <td>iOS App; Swift und SwiftData; API-Anbindung (REST) und Statemangement; Styling/ Endpunkte; Datenbank-Anbindung; End-To-End Testing (Postman)</td>
      <td>25</td>
      <td>5</td>
      <td>65</td>
      <td>95</td>
    </tr>
    <tr>
      <td>Merch Front-/BackEnd (Sprint)</td>
      <td>iOS App; Swift und SwiftData; API-Anbindung (REST) und Statemangement; Styling/ Endpunkte; Datenbank-Anbindung; End-To-End Testing (Postman)</td>
      <td>15</td>
      <td>18</td>
      <td>22</td>
      <td>45</td>
    </tr>
     <tr>
      <td>User Front-/BackEnd (Sprint)</td>
<td>iOS App; Swift und SwiftData; API-Anbindung (REST) und Statemangement; Styling/ Endpunkte; Datenbank-Anbindung; End-To-End Testing (Postman)</td>
      <td>13</td>
      <td>8</td>
      <td>8</td>
      <td>29</td>
    </tr>
     <tr>
      <td>Cart Front-/BackEnd (Sprint)</td>
      <td>iOS App; Swift und SwiftData; API-Anbindung (REST) und Statemangement; Styling/ Endpunkte; Datenbank-Anbindung; End-To-End Testing (Postman)</td>
      <td>5</td>
      <td>5</td>
      <td>8</td>
      <td>18</td>
    </tr>
    <tr>
      <td>Sprintplanung</td>
      <td>Planung, Einträge und Workflow verfolgen auf Jira</td>
      <td>8</td>
      <td>8</td>
      <td>8</td>
      <td>24</td>
    </tr>
    <tr>
      <td>SRS</td>
      <td>Projektplanung und Festsetzung der Vision und Konkretisierung der Manifestierung der Applikation</td>
      <td>5</td>
      <td>10</td>
      <td>2</td>
      <td>17</td>
    </tr>
    <tr>
      <td>Klassendiagramme</td>
      <td>Erfassen, analysieren und visualisieren der Klassen, der Relationen und das Versionieren</td>
      <td>12</td>
      <td>0</td>
      <td>2</td>
      <td>14</td>
    </tr>
    <tr>
      <td>Use Case/User Story</td>
      <td>Nutzerverhalten und Bedienbarkeit der App durch Definition der Vorgänge</td>
      <td>0</td>
      <td>5</td>
      <td>5</td>
      <td>10</td>
    </tr>
    <tr>
      <td>ASR</td>
      <td>Diskussion und Festlegung der Architektur und -entscheidung</td>
      <td>0</td>
      <td>5</td>
      <td>0</td>
      <td>5</td>
    </tr>
    <tr>
      <td>RUP SAD</td>
      <td>Dokumentation für bisherige Architektur und spezifische Umsetzung</td>
      <td>5</td>
      <td>0</td>
      <td>0</td>
      <td>5</td>
    </tr>
    <tr>
      <td>RMMM</td>
      <td>Erfassung der Risiken, bewältigungstrategien und Erstellung der Visualisierungen/td>
      <td>0</td>
      <td>5</td>
      <td>0</td>
      <td>5</td>
    </tr>
    <tr>
      <td>RMMM</td>
      <td>Erfassung der Risiken, bewältigungstrategien und Erstellung der Visualisierungen/td>
      <td>0</td>
      <td>5</td>
      <td>0</td>
      <td>5</td>
    </tr
    <tr>
      <td>Planung, Kommunikation</td>
      <td>Zeit, die in Planung, Kommunikation, Koordination und Review gingen</td>
      <td>3</td>
      <td>3</td>
      <td>15</td>
      <td>21</td>
    </tr>
    <tr>
      <td>Zusammenfassung</td>
      <td>Stunden pro Person</td>
      <td>= 58</td>
      <td>= 41</td>
      <td>= 87</td>
      <td>= 186</td>
    </tr>
  </tbody>
</table>


### Hauptbeiträge von jedem Teammitglied (in eigenen Worten)
Hier werden in wenigen eigenen Worten von den Teammitgliedern die Hauptbeiträge selbst beschrieben.

#### Robin Schwenzfeier
Ich habe mich ausschließlich um das FrontEnd gekümmert, die Aufgaben verteilt, die Qualitätssicherung übernommen und Teile der Dokumentation übernommen.
Im BackEnd kam noch Code Review hinzu und Feedback durch die entstehende Nutzung im FrontEnd.
Versionierung und Organisation der Dokumentation, sowie die Kommunikation und Terminplanung habe ich ebenfalls übernommen.

####  Mael Dossoh
Hauptsächlich habe ich mich um die Dokumentation des Projekts gekümmert sowie die Erstellung und Aktualisierung das SRS und das ASR.
Des weiteren habe ich den Merch-Endpunkt der Datenbank angelegt und mich die Verbindung zum Frontend gekümmert.

#### Niklas Krauth
Größtenteils habe ich mich um das BackEnd gekümmert welches ich erstellt habe sowie die grundlegende Architektur und die Corgi-Endpunkte dort. Auch habe ich mich um die Datenbank gekümmert. Dazu wurden auch die meisten Diagramme von mir erstellt.

## Architektur
Das [ASR (https://github.com/mausio/corgi-shop-doc/blob/main/ASR%20Document.md)](https://github.com/mausio/corgi-shop-doc/blob/main/ASR%20Document.md) geht ausführlicher auf die Architektur ein.
Jedoch, im Kurzen, ist die Architektur wie folgt aufgebaut:
- FrontEnd: Swift, SwiftUI und SwiftData bilden den View und Teile vom Controller (Actions, die dispatched werden) und beziehen Daten bei Bedarf vom BackEnd.
- BackEnd: Spring Boot, Java und MySQL bilden das Model und den Controller und stellen die Daten für das FrontEnd bereit.

## Tech Stacks
Genutzte Tech Stacks:

### BackEnd

- Spring Boot
- Java
- MySQL
- Postman
- TablePlus
- IntelliJ IDEA
- Git
- Github
- Docker

### FrontEnd

- Xcode
- Swift 
- iOS
- Spring Boot (BackEnd als REST API)
- Git
- Github