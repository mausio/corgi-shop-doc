## Architecture Significant Requirements Document ##
Architecture Significant Requirements (ASR) sind spezifische Anforderungen, die einen wesentlichen Einfluss auf die Architektur eines Software-Systems haben. 
Diese Anforderungen haben entscheidende Auswirkungen auf die Struktur, das Design und die Entscheidungen in Bezug auf die Architektur des Systems. 
Im Allgemeinen sind ASRs Schlüsselelemente, die Entwickler berücksichtigen müssen, um ein effektives und qualitativ hochwertiges System zu produzieren.

Anbei veranschaulichen wir diese ASR im Bezug auf unser Projekt:
- Erstens präsentieren wir unseren Utility Tree.
- Zweitens stellen wir unsere Softwareentscheidungen vor.

## Utility Tree ##

Ein Utility Tree ist in der Softwareentwicklung eine Darstellung, die dazu dient, die Nutzwerte verschiedener Optionen oder Entscheidungen in Bezug auf bestimmte Kriterien zu vergleichen.
Er wird verwendet, um komplexe Entscheidungen zu strukturieren, indem er die verschiedenen Aspekte einer Entscheidung in einer hierarchischen Baumstruktur organisiert.
Die Wertgkeiten werden durch Niedrig (⭐) Mittel (⭐⭐) und Hoch (⭐⭐⭐) dargestellt.

| Q-Attribut          | Verfeinerung                  | Qualitätsattributszenarien                                     | Geschäftswert | Technisches Risiko |
|---------------------|-------------------------------|------------------------------------------------------------------|---------------|--------------------|
| **Interoperability**| API-Spezifikation             | Auf localhost:8080/api können Endpunkt-Spezifikationen eingesehen werden. | ⭐⭐ | ⭐         |
| **Modifiable**  | Granular strukturiertes Backend| Durch die standardisierte Verwendung von Spring Boot und einem relationalen Datenbankschema ist das Backend leicht erweiterbar. | ⭐⭐⭐      | ⭐⭐⭐           |
| **Useability** | Intuitives Design         | Die Website führt den Benutzer durch ihr intuitives und einfaches Design. | ⭐⭐⭐      | ⭐⭐          |
| **Testability**      | Testframeworks                | Während der Entwicklungsphase verwenden wir automatisierte Tests, um unsere Qualitätsanforderungen zu erfüllen. | ⭐⭐⭐      | ⭐⭐          |

## Architektur Entscheidungen ##

- **1 Java**
  - Wir haben uns für Java als Backendsprache entschieden, weil es eine bewährte, plattformunabhängige und robuste Programmiersprache ist. Mit Java können wir skalierbare und zuverlässige Anwendungen entwickeln, was für die Performance und Stabilität unseres Systems entscheidend ist.

- **2 Spring Boot**
  - Spring Boot ermöglicht eine schnelle Integration von Diensten und vereinfacht die Konfiguration, was zu einer beschleunigten Entwicklungszeit beiträgt.

- **3 PostgresSQL (TablePlus)**
  - PostgresSQL als relationale Datenbank, kombiniert mit TablePlus als Datenbankmanagement-Tool, wurde gewählt, um eine robuste, ACID-konforme Datenbanklösung zu gewährleisten. TablePlus erleichtert zudem eine benutzerfreundliche und effiziente Datenbankverwaltung.

- **4 Granulares Datenbankschema**
  - Die Entscheidung für ein granulares Datenbankschema unterstreicht unser Bestreben nach Erweiterbarkeit und Flexibilität. Durch die Strukturierung der Datenbank in granulare Einheiten schaffen wir eine solide Grundlage für die Skalierung und die nahtlose Integration neuer Funktionen.

- **5 Swift**
  - Swift bietet optimierte Performance und ist die bevorzugte Sprache für die Entwicklung von iOS-Apps.

- **6 iOS Kits**
  - Die Integration von iOS Kits in unseren Frontend-Tech-Stack ermöglicht uns die Nutzung nativer iOS-Bibliotheken und Frameworks. Dies gewährleistet eine enge Integration mit der iOS-Plattform und eröffnet uns den Zugriff auf spezifische Funktionen.

- **7 SwiftData**
  - Die Entscheidung für SwiftData zeigt unsere Absicht, eine effiziente Datenverarbeitung und -verwaltung auf der iOS-Plattform zu gewährleisten. SwiftData bietet uns die Werkzeuge, um Daten in unserer Anwendung effektiv zu handhaben.

Insgesamt basieren unsere Architekturentscheidungen darauf leistungsfähige und benutzerfreundliche Funktionen für unseren "Corgi-Shop" zu entwickeln. 
Unsere Kombination von bewährten Technologien ist darauf ausgerichtet, eine Anwendung zu schaffen, die nicht nur stabil und skalierbar ist, sondern auch optimal auf die Zielplattform, in diesem Fall iOS, zugeschnitten ist.
