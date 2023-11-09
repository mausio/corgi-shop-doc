# Use-Case Realization Specification: User-Login
Dieses Dokument beschreibt den Vorgang beim Login eines*r User.

## 1. Beschreibung
Ein*e User hat die Möglichkeit Corgis sich zu merken (mit einem Stern), einen Corgi in den Cart hinzuzufügen und einen Checkout zu performen.
Dafür muss ein Profil eingelogt sein. Dieser Vorgang findet auf dem HomeTab statt. 

### 1.1 Screenshot

### 1.2 Scope
Scope des Logins:
- User füllt die Logindaten (Mail, Passwort) aus
- Bei positiver Response wird der*die User eingelogt vor Ort und bekommt die Stammdaten angezeigt
- Der*die User kann nun den Einkauf fortsetzen

### 2. Flow of Events
Flow of Events beschreibt den Verlauf zwischen Interaktion der*des User und den technisches Hintergrundprozessen beim Login

#### 2.1 Mail und Passwort eingeben und abschicken
Der*die User gibt seine/ihre Credentails (Mail, Passwort) ein und per Druck auf den "Login"-Button wird der Login performed. Die Daten werden in ein JSON Objekt umgewandelt und als Body zum POST-HTTP-Methode ans Back End gesendet, wo überprüft wird, ob solch ein/e User existiert. 

#### 2.2 Positive Antwort
Im Falle, dass dies der Wahrheit entspricht, wird ein Token & der HTTP Status 200 zurückgeschickt, der den/die User verifiziert und wird im Front End gespeichert. 
Der/Die User hat nun erweiterte Rechte.

#### 2.3 Negative Antwort
Im Falle, dass es kein*e User im Back End bzw. in der Datenbank existiert, wird der HTTP Status 401 zurückgegeben. 
Der/dem User wird angezeigt, dass Passwort und/oder Mail falsch sind.

### 3. Sequenzdiagramm
[//]: # (TODO Login-Aktivitätdiagramm ergänzen)
