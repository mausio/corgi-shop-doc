# Use-Case Realization Specification: Corgi List

## 1. Beschreibung
CorgiList ermöglicht es Users eine Liste von Corgis im Corgi-Shop unter dem Reiter "Corgis" anzuzeigen. 
Die Liste wird auf der Benutzeroberfläche angezeigt und zeigt verschiedene Informationen zu den verfügbaren Corgis wie den Namen.
Desweiteren kann der User auf einzelne Corgis klicken und wird auf die Corgi-Page weitergeleitet, wo er weitere Informationen zu dem Corgi einsehen kann.
[Dies ist weiter beschrieben in dem Use-Case Realization Specification: CorgiDetails]

### 1.1 Screenshot
<img width="326" alt="Screenshot_2023-10-30_at_11 36 43" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/f8f03db9-143a-428a-b439-bd6680693d1c">


### 2. Flow of Events
Der Ablauf der Ereignisse im Zusammenhang mit der CorgiList ist wie folgt:
\n
- User landet auf Home-Page und kann in der unteren Leiste (TabView) navigieren
- User kann auf "Corgis" klicken und landet auf der Corgi-Page
- Corgis werden aus dem BackEnd gefetcht und mit SwiftData aufbereitet
- CorgiList wird im FrontEnd angezeigt (mit Namen und Bild)
- User kann auf einzelne Corgis klicken und wird auf die CorgiDetail-Navigation weitergeleitet

### 3. Sequenzdiagramm
[Hier wird das Sequenzdiagramm eingefügt um die Interaktionen zwischen dem User und der CorgiList zu veranschaulichen]