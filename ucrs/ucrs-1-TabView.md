# Use-Case Realization Specification: TabView für Interaktionen

## 1. Beschreibung
Der TabView (untere Leiste) stellt die Interaktion und Navigation des Users in der App dar, wobei dieser über das clicken visuell von Seite zu Seite springt und verschiedene Aktionen performen kann. 
Desweitern ist der TabView hard-coded und wird in der App nicht verändert, weshalb er nicht in der Datenbank gespeichert wird und somit nicht im BackEnd verwaltet werden muss.

### 1.1 Screenshot
<img width="326" alt="Screenshot_2023-10-30_at_11 36 38" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/4283b343-cbdc-442f-9b5c-ae40a891db27">

### 1.2 Scope
Der TabView ermöglicht es dem User in der App zu navigieren und verschiedene Aktionen zu performen.

### 1.3 Definitionen, Abkürzungen und Begriffe
- TabView: untere Leiste in der App, die die Navigation des Users ermöglicht (iOS/SwiftUi spezifische Benennung)

### 2. Flow of Events
Der Ablauf der Ereignisse im Zusammenhang mit dem TabView ist wie folgt:
\n
- User landet auf Home-Page und kann in der unteren Leiste navigieren
- User kann auf Corgis klicken und landet auf der Corgi-Page
- User kann auf Merch klicken und landet auf der Merch-Page
- User kann auf Checkout klicken und landet auf der Checkout-Page

### 3. Sequenzdiagramm
<img width="524" alt="Bildschirmfoto_2023-10-30_um_12 28 48" src="../images/sq_Corgi.png">
<img width="524" alt="Bildschirmfoto_2023-10-30_um_12 28 48" src="../images/sq_Merch.png">
<img width="524" alt="Bildschirmfoto_2023-10-30_um_12 28 48" src="../images/sq_Checkout.png">
