# **Meisterschule Elektrotechnik**

## Inhaltsverzeichnis
- [**Meisterschule Elektrotechnik**](#meisterschule-elektrotechnik)
  - [Inhaltsverzeichnis](#inhaltsverzeichnis)
  - [SPS](#sps)
    - [1. Was ist eine SPS?](#was-ist-eine-sps)
    - [2. Wie erstelle ich ein Projekt?](#wie-erstelle-ich-ein-projekt)
    - [3. Erste Schritte](#3-erste-schritte)

---

## SPS

### Was ist eine SPS?
> <font color="#fff">Eine speicherprogrammierbare Steuerung (**SPS**; englisch: programmable logic controller, PLC) ist ein Gerät, das zur [Steuerung](https://de.wikipedia.org/wiki/Steuerungstechnik) oder [Regelung](https://de.wikipedia.org/wiki/Regelungstechnik) einer Maschine oder Anlage eingesetzt und auf digitaler Basis [programmiert](https://de.wikipedia.org/wiki/Programmierung) wird. Sie löst die festverdrahtete [verbindungsprogrammierte Steuerung](https://de.wikipedia.org/wiki/Verbindungsprogrammierte_Steuerung) in den meisten Bereichen ab.</font>
Quelle: [Wikipedia](https://de.wikipedia.org/wiki/Speicherprogrammierbare_Steuerung)

### Wie erstelle ich ein Projekt?
- **Schritt 1.)** Öffne den <font color="#FD5959">SIMATIC Manager</font>.<br>
  <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 2.)** Wenn der Installationsassistent geöffnet ist, klicke auf \textcolor{red}{Weiter}.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 3.)**  Bei dem <font color="#FD5959">CPU-Typ</font> wählen wir die <font color="#FD5959">CPU314</font> aus und klicken auf <font color="#FD5959">Weiter</font>.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 4.)** Die <font color="#FD5959">Sprache für angewählte Bausteine</font> setzen wir auf <font color="#FD5959">AWL</font>, falls nicht bereits ausgewählt.<br>
Anschließend klicken wir auf <font color="#FD5959">Weiter</font>.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 5.)** Nun geben wir bei <font color="#FD5959">Projektname</font> dem Projekt einen Namen.<br>
Zuletzt bestätigen wir unsere Angaben mit <font color="#FD5959">Fertigstellen</font>.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

### 3. Erste Schritte
- **Schritt 1.)** In unserem neu erstellten Projekt machen wir nun einen <font color="#FD5959">Rechtsklick</font> in das große weiße Feld und wählen unter <font color="#FD5959">Neues Objekt einfügen</font> > <font color="#FD5959">Funktion</font>.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 2.)** In folgendem Fenster ändern wir die <font color="#FD5959">Erstellsprache</font> zu <font color="#FD5959">FUP</font> und bestätigen mit <font color="#FD5959">OK</font>.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 2.1.)** Der Baustein <font color="#FD5959">FC1</font> sollte nun im Fenster auftauchen.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 3.)** Nun öffnen wir den <font color="#FD5959">OB1</font> mit einem <font color="#FD5959">Doppelklick</font>.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 4.)** Es öffnet sich folgendes Fenster.<br>
In das <font color="#FD5959">Netzwerk 1</font> schreiben wir nun <font color="#FD5959">CALL FC1</font> und bestätigen dies mit <font color="#FD5959">ENTER</font>.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">

- **Schritt 5.)** Anschließend <font color="#FD5959">speichern</font> wir den Baustein und <font color="#FD5959">schließen</font> das Fenster.<br>
<img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="(Bild: SIMATIC Manager)" width="300" height="auto">
