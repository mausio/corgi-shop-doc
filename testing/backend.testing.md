# Testing im BackEnd

1. Welche Arten von Tests werden eingesetzt?
    - Unit-Tests: Testen einzelner Methoden
    - Datenbank-Tests: Testen von Datenbankabfragen
    - API-Tests: Testen der Endpunkte

2. Schwierigkeiten bei der Testabdeckung?
   - Nicht alle Methoden oder Klassen, wie zum Beispiel Entitäten oder Interfaces können getestet werden, dadurch leidet die Testabdeckung
   - Der angezeigte Prozentsatz der Testabdeckung in IntelliJ hat Fehler womit es sein kann das die Zahl nicht korrekt ist
   -> Dadurch muss mehrmals getestet werden

3. Wie wird die Testabdeckung gemessen?
   - IntelliJ IDEA Ultimate (unsere IDE) verfügt über eine Testabdeckung für die Programmiersprache Java, mit ihr wird gemessen
  
4. Was ist der Zielwert für die Testabdeckung?
   - Ein konkreten Zielwert gibt es nicht aber es wird versucht auf eine Testabdeckung von 80% hingearbeitet

5. Wie werden die Testfälle verwaltet? Welche Testfälle sind bestanden/fehgeschlagen, basierend auf der Version des Quellcodes/Deployments?
  - Es sollten immer alle Tests bestanden werden
  - Werden Tests nicht bestanden, so muss der geteste Code umgeschrieben werden
  - Für jede File wird eine entsprechende Test-Datei erstellt, die die Funktionalität der File testet
  
