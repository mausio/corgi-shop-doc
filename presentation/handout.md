# Handout zur Präsentation "Corgi Shop"

Dieses Handout enthält die wichtigsten Informationen zur Präsentation "Corgi Shop". Dazu gehören folgende Informationen:

- Projektnamen
- Projektbeschreibung
- Projektteam und Arbeitsteilung
- Statistiken über Aufwände
- Overall Use Case Diagramm
- Architektur
- Tech Stacks
- Techniken zur Dokumentation
- Techniken zur Projektverwaltung

## Projektnamen

Der gewählte Projektnamen lautet "Corgi Shop".

## Projektbeschreibung

Der Corgi Shop ist eine iOS App, die sich auf den Verkauf von Corgis spezialisiert hat.
Der Shop bietet eine Vielzahl von Corgis an und Merch, der in unterschiedliche Kategorien unterteilt ist.
Der Kunde kann die Corgis oder den Merch in den Warenkorb legen und anschließend bestellen.

## Projektteam und Arbeitsteilung

Das Projektteam besteht aus folgenden Mitgliedern:

- Mael Dossoh: BackEnd, CI/CD, Dokumentation
- Niklas Krauth: BackEnd, Database, Migration
- Robin Schwenzfeier: FrontEnd, Teamleader

## Statistiken über Aufwände

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
      <td>19</td>
      <td>2</td>
      <td>0</td>
      <td>21</td>
    </tr>
    <tr>
      <td>Niklas Krauth</td>
      <td>6</td>
      <td>10</td>
      <td>0</td>
      <td>16</td>
    </tr> 
    <tr>
      <td>Robin Schwenzfeier</td>
      <td>9</td>
      <td>3</td>
      <td>5</td>
      <td>17</td>
    </tr>
  </tbody>
</table>

### Stunden

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Beschreibung </th>
      <th>Niklas</th>
      <th>Mael</th>
      <th>Robin</th>
      <th>Gesamt</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Corgis BackEnd (Sprint)</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Corgis FrontEnd (Sprint)</td>
      <td></td>
      <td></td>
      <td></td>
      <td>60</td>
      <td></td>
    </tr>
    <tr>
      <td>Merch BackEnd (Sprint)</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sprintplanung</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>SRS</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Klassendiagramme</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Use Case / User Story</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ASR</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Utility Tree</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>RUP SAD</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Zusammenfassung</td>
      <td>Stunden pro Person</td>
      <td>= </td>
      <td>=</td>
      <td>=</td>
      <td>-</td>
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

#### Niklas Krauth

## Overall Use Case Diagramm
![ucd1](https://github.com/mausio/corgi-shop-doc/assets/122524882/3a5d41ba-8358-4f5e-aacd-e3df6feb296a)

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

## Techniken zur Dokumentation

- Markdown Language
- Github Discussions

## Techniken zur Projektverwaltung
- Jira
