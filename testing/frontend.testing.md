# Testing im FrontEnd

1.Welche Arten von Tests werden eingesetzt?
  - Alle Tests nutzen das XCTest Framework von Apple
  - Unit-Tests: Testen einzelner Funktionen oder Methoden, wenn vorhanden
    - Momentan gibt es keine Funktionen, die getestet werden können
  - Integrationstests: Testen, ob die Komponenten zusammenarbeiten
    - Momentan gibt es z.B. kein Login, der getestet werden könnte
    - Der korrekte Aufruf der API wird getestet (z.B. ob die Corgis korrekt geladen werden)
  - UI-Tests: Testen die Benutzeroberfläche
    - Testkriterien:
      - Testen, ob die Benutzeroberfläche korrekt angezeigt wird
      - Testen, ob die Benutzeroberfläche korrekt reagiert
      - Testen, ob die Benutzeroberfläche korrekt interagiert
      - Testen, ob die Benutzeroberfläche korrekt navigiert
    -  Momentan werden nur die Interaktionen mit der Navigation-Bar getestet und die Navigation in den Pages selbst

2.Schwierigkeiten bei der Testabdeckung?
  - Das Testing beruht einzig und allein auf das XCTest Framework von Apple, welches eingeschränkt ist
  - Es gibt keine Funktionen, die getestet werden können
  - Die Arts von Tests ist eingeschränkt durch das Framework
  - Eine hohe Testabdeckung ist nicht möglich, da die Funktionen fehlen

3.Wie wird die Testabdeckung gemessen?
  - Ein Apple-Tool, welches die Testabdeckung misst, wird verwendet
    - Problem: Es ist schleierhaft, wie die Testabdeckung gemessen wird


4.Was ist der Zielwert für die Testabdeckung? 
  - Aus Erfahrungswerten der praktischen Tätigkeit: 70% Testabdeckung

5.Welche automatischen Testwerkzeuge werden verwendet?
  - XCTest Framework von Apple

6.Wie werden die Testfälle verwaltet? Welche Testfälle sind bestanden/fehgeschlagen, basierend auf der Version des Quellcodes/Deployments?
  - Es sollten immer alle Tests bestanden werden; Werden Tests nicht bestanden, so darf der Code nicht freigegeben bzw committed werden

