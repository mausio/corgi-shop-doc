# Review des Corgi-Shop-Backend

Datum: 3. Juni 2024
Startzeit: 13.30 Uhr
Endzeit: 15 Uhr

Teilnehmer: Mael Dossoh (Backend-Entwickler), Niklas Krauth (Backend-Entwickler), Robin Schwenzfeier (Moderator), Lukas Melcher (Externer Entwickler/Reviewer)

Ziel/Fokus der Review: Für die Review wurden alle Abschnitte des Backends, abgesehen von Basic Auth, ausgewählt. Dies liegt daher dass das Backend verbesserungspotenziall besitzt (basiernd auf den Ergebnissen der Metriken), dazu können die meisten externen Entwickler eher Java programmieren als Swift.

Komponenten für Review: Alle Entitäten wie Corgi, Item, User, usw.; Alle Services wie CorgiService, CategoryService, UserService, usw.; Alle Repositories wie CorgiRepoitory, UserRepository, usw.; Alle RestController wie CorgiRestController, CategoryRestController, usw.;
Kriterien für Review: Codequalität, Sauberkeit, Skalierbarkeit, Wartbarkeit, Redundanz

Review Methodik: Walktrough/Code Review, alle ausgewählten Kompontene werden hierarchisch reviewt

## Ergebnis: 

Codequalität:
- Die Verzeichnisstruktur ist klar und zeigt eine gute Schichtentrennung auf.
- DTOs, Entitäten und Repositories sind gut organisiert und leicht verständlich.
Verbesserungspotential:
- Einige der Methoden könnten durch Kommentare besser dokumentiert werden.

Sauberkeit:
- Saubere Trennung der Konfigurations- und Sicherheitsaspekte.
- Die Entitäten und Repositories sind klar voneinander getrennt.
Verbesserungspotential:
- Sicherstellen, dass alle Klassen sinnvolle und konsistente Kommentare enthalten.

Skalierbarkeit:
- Die Nutzung von Spring Boot ermöglicht eine einfache Skalierung der Anwendung.

Wartbarkeit:
- Klare Trennung zwischen den Schichten macht aufkommende Wartungen einfacher.

Redundanz:
- Gut strukturierte Services und Repositories, welche die Redundanz minimieren.

## Fazit
Das Backend ist gut strukturiert und nutzt gut bewährte Frameworks und Praktiken. Es gibt jedoch Raum für Verbesserungen im Bereich der Dokumentation. Insgesamt ein sehr gut aufgebautes Backend, welches durch gezielte Maßnahmen die Qualität und Wartbarkeit des Codes weiter steigern könnte, um es noch „besser“ zu machen.
