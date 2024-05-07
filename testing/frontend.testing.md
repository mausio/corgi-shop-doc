# Testing im FrontEnd

1.Welche Arten von Tests werden eingesetzt?
  - Alle Tests nutzen das XCTest Framework von Apple
  - Unit-Tests: Testen einzelner Funktionen oder Methoden, wenn vorhanden
    - Momentan gibt es keine Funktionen, die getestet werden können, da die jeweiligen einzelne Funktionen Teil vom XCTest Framework sind und somit schon Seiten Apples getestet wurden und das erneute Testen von Standardfunktionen ist weder effektiv, noch effizient
    - Es existieren keine andere Funktionen, die mehr Aufgaben übernehmen als z.B. das Togglen von Boolsche Werte
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
-> Alle Arten von Tests werden in dem Projekt unter [dem FrontEnd Repository](https://github.com/mausio/corgi-shop-front-end) vom Corgi-Shop aufgeführt, jeweils unter den Ordner "Tests" und "UITests" und sind in der Programmiersprache Swift geschrieben, welche dem Testplan selbst unterlegen. Um die Tests sinnvoll auszuführen, wird XCode benötigt, welches auf einem Mac installiert werden muss.

2.Schwierigkeiten bei der Testabdeckung?
  - Das Testing beruht einzig und allein auf das XCTest Framework von Apple, welches eingeschränkt ist
  - Es gibt keine Funktionen, die getestet werden können
  - Die Arts von Tests sind eingeschränkt durch das Framework
  - Das Testing von Seiten Apples ist sehr proprietär, eigenartig und eingeschränkt
  - Die Zeit, die benötigt wird zum Testen ist sehr hoch, da erst der Testplan geladen wird, die App gestartet wird, Daten gefetched werden und dann die Tests durchgeführt werden, nacheinander. Dies benötigt sehr viel Zeit und ist "ineffizient".

3.Wie wird die Testabdeckung gemessen?
  - Ein Apple-Tool, welches die Testabdeckung misst, wird verwendet
    - Problem: Es gibt kein Apple-Tool, welches die Testabdeckung misst (zumindest nicht mehr in der aktuellen Version von XCode)


4.Was ist der Zielwert für die Testabdeckung? 
  - Aus Erfahrungswerten der praktischen Tätigkeit: 70% Testabdeckung
    - Problem: Es gibt keine Testabdeckung, die gemessen werden kann, da es kein Apple-Tool gibt, welches die Testabdeckung misst (zumindest nicht mehr in der aktuellen Version von XCode)

5.Welche automatischen Testwerkzeuge werden verwendet?
  - XCTest Framework von Apple

6.Wie werden die Testfälle verwaltet? Welche Testfälle sind bestanden/fehgeschlagen, basierend auf der Version des Quellcodes/Deployments?
  - Es sollten immer alle Tests bestanden werden; Werden Tests nicht bestanden, so darf der Code nicht freigegeben bzw committed werden
  - Für jede File wird eine entsprechende Test-Datei erstellt, die die Funktionalität der File testet

