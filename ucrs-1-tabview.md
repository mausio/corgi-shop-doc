# Use-Case Realization Specification: <TabView für Interaktionen>

## 1. Beschreibung
Der TabView (untere Leiste) stellt die Interaktion und Navigation des Users in der App dar, wobei dieser über das clicken visuell von Seite zu Seite springt und verschiedene Aktionen performen kann. 
Desweitern ist der TabView hard-coded und wird in der App nicht verändert, weshalb er nicht in der Datenbank gespeichert wird und somit nicht im BackEnd verwaltet werden muss.

### 1.1 Screenshot
<img width="326" alt="Screenshot_2023-10-30_at_11 36 38" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/4283b343-cbdc-442f-9b5c-ae40a891db27">

### 2 Flow of Events
- User landet auf Home-Page und kann in der unteren Leiste navigieren
- User kann auf Corgis klicken und landet auf der Corgi-Page
- User kann auf Merch klicken und landet auf der Merch-Page
- User kann auf Checkout klicken und landet auf der Checkout-Page

### Sequenzdiagramm