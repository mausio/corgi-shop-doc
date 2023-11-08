# Use-Case Realization Specification: Corgi-Tab
Dieses Dokument beschreibt die Interaktionen und den Dialog hinter dem Corgi-Tab.

## 1. Beschreibung
Der "Corgi-Tab" (oder auch "Corgi-Page" genannt) zeigt die verfügbaren Corgis des Shops in einer Liste an.
Des weiteren kann der*die User per Click auf einen Corgi in einem DetailView aufrufen.

### 1.1 Screenshot
<img width="200" alt="Screenshot_2023-10-30_at_11 36 38" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/4283b343-cbdc-442f-9b5c-ae40a891db27">
<img width="200" alt="Screenshot_2023-10-30_at_11 36 43" src="https://github.com/mausio/corgi-shop-doc/assets/122524882/f8f03db9-143a-428a-b439-bd6680693d1c">

### 1.2 Scope
Der Scope ist wie folgt:
- Per Click auf den Corgi-Tab soll eine Liste dem*der User angezeigt werden
- Bei weiterem Click, auf einen Corgi, wird ein DetailView geöffnet, wo Details wie Preis, Gewicht usw aufgeführt wird
- Auch gibt es hier die Möglichkeit auf den Cart um den Corgi in den Cart zu befördern
- Der Stern ermöglicht es den Corgi sich zu merken

### 1.3 Definitionen, Abkürzungen und Begriffe
- 


### 2. Flow of Events
Flow of Events beschreibt den Verlauf zwischen Interaktion der*des User und den technisches Hintergrundprozessen.

#### 2.1 Corgi-List
Beim Click auf den Tab "Corgis" wird der Corgi-Tab geladen und es werden aus dem Back End das entsprechende Array an Objekten gefetched.
Im Back End holt Spring Boot die entsprechenden Daten aus einer Datenbank und baut die Objekte zusammen und returned sie ans Front End, wo sie im State gehalten werden.


#### 2.2 Corgi-DetailView
Beim Clicken auf einen Corgi aus der Liste wird der entsprechende Corgi im DetailView aufgeführt und erhält das entsprechende Objekt aus der Liste.

[//]: # (TODO Cart ergänzen "#### 2.3 In den Cart hinzufügen")

[//]: # (TODO Merken ergänzen "#### 2.4 Corgi merken")

### 3. Sequenzdiagramm
<img width="524" alt="Bildschirmfoto_2023-10-30_um_12 28 48" src="../images/sq_Corgi.png">
<img width="524" alt="Bildschirmfoto_2023-10-30_um_12 28 48" src="../images/sq_Merch.png">
<img width="524" alt="Bildschirmfoto_2023-10-30_um_12 28 48" src="../images/sq_Checkout.png">
