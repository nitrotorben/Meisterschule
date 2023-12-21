# **Meisterschule Elektrotechnik**

<details>
    <summary>Inhaltsverzeichnis</summary>
    &#8226;&ensp;SPS<br>
    &emsp;&emsp;&#9702;&ensp;1. Was ist eine SPS?<br>
    &emsp;&emsp;&#9702;&ensp;2. Wie erstelle ich ein Projekt?<br>
    &emsp;&emsp;&#9702;&ensp;3. Aufgaben<br>
    &emsp;&emsp;&emsp;&emsp;&#8729;&ensp;3.1. RS-Flip Flop<br>
    &emsp;&emsp;&emsp;&emsp;&#8729;&ensp;3.2. Generator mit 4 Motoren<br>
    &emsp;&emsp;&emsp;&emsp;&#8729;&ensp;3.3. Torantrieb<br>
    &emsp;&emsp;&emsp;&emsp;&#8729;&ensp;3.4. Kläranlage mit 2 Pumpen und Schieber<br>
</details>

---

<details>
    <summary><h1>SPS</h1></summary>    
    <details>
        <summary><h3>Inhaltsverzeichnis</h3></summary>
        &#9702;&ensp;1. Was ist eine SPS?<br>
        &#9702;&ensp;2. Wie erstelle ich ein Projekt?<br>
        &#9702;&ensp;3. Erste Schritte<br>
        &#9702;&ensp;4. Aufgaben<br>
        &emsp;&emsp;&#8729;&ensp;3.1. RS-Flip Flop<br>
        &emsp;&emsp;&#8729;&ensp;3.2. Generator mit 4 Motoren<br>
        &emsp;&emsp;&#8729;&ensp;3.3. Torantrieb<br>
        &emsp;&emsp;&#8729;&ensp;3.4. Kläranlage mit 2 Pumpen und Schieber<br>
    </details>
    <details>
        <summary><h2><u>1. Was ist eine SPS?</u></h2></summary>
        <figure>
            <blockquote>
                Eine <b>speicherprogrammierbare Steuerung</b> <b>SPS</b>; englisch: <i>programmable logic controller</i>, <i>PLC</i>) ist ein Gerät, das zur <a href="https://de.wikipedia.org/wiki/Steuerungstechnik">Steuerung</a> oder <a href="https://de.wikipedia.org/wiki/Regelungstechnik">Regelung</a> einer Maschine oder Anlage eingesetzt und auf digitaler Basis <a href="https://de.wikipedia.org/wiki/Programmierung">programmiert</a> wird. Sie löst die „festverdrahtete“ <a href="https://de.wikipedia.org/wiki/Verbindungsprogrammierte_Steuerung">verbindungsprogrammierte Steuerung</a> in den meisten Bereichen ab.
            </blockquote>
            <figcaption>Quelle: <a href="https://de.wikipedia.org/wiki/Speicherprogrammierbare_Steuerung">Wikipedia</a></figcaption>
        </figure>
    </details>

<details>
    <summary><h2><u>2. Wie erstelle ich ein Projekt?</u></h2></summary>
    <h3>Schritt 1.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Öffne den}}$ $\color{#FD5959}{\textsf{SIMATIC Manager}}$.</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 2.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Wenn der Installationsassistent geöffnet ist, klicke auf}}$ $\color{#FD5959}{\textsf{Weiter}}$.</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 3.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Bei dem}}$ $\color{#FD5959}{\textsf{CPU-Typ}}$ $\color{#D6DEE3}{\textsf{wählen wir die}}$ $\color{#FD5959}{\textsf{CPU314}}$ $\color{#D6DEE3}{\textsf{aus und klicken auf}}$ $\color{#FD5959}{\textsf{Weiter}}$.</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 4.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Die}}$ $\color{#FD5959}{\textsf{Sprache für angewählte Bausteine}}$ $\color{#D6DEE3}{\textsf{setzen wir auf}}$ $\color{#FD5959}{\textsf{AWL}}$ $\color{#D6DEE3}{\textsf{, falls nicht bereits ausgewählt.}}$<br>
            $\color{#D6DEE3}{\textsf{Nun klicken wir auf}}$ $\color{#FD5959}{\textsf{Weiter}}$.</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 5.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Nun geben wir bei}}$ $\color{#FD5959}{\textsf{Projektname}}$ $\color{#D6DEE3}{\textsf{dem Projekt einen Namen.}}$<br>
            $\color{#D6DEE3}{\textsf{Zuletzt klicken wir auf}}$ $\color{#FD5959}{\textsf{Fertigstellen}}$.</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
</details>

<details>
    <summary><h2><u>3. Erste Schritte</u></h2></summary>
    <h3>Schritt 1.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{In unserem neu erstellten Projekt machen wir nun einen}}$ $\color{#FD5959}{\textsf{Rechtsklick}}$ $\color{#D6DEE3}{\textsf{in das große weiße Feld, und wählen unter}}$ $\color{#FD5959}{\textsf{Neues Objekt einfügen }}$ $\color{#D6DEE3}{\textsf{>}}$ $\color{#FD5959}{\textsf{Funktion}}$.</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 2.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{In folgendem Fenster ändern wir die}}$ $\color{#FD5959}{\textsf{Erstellsprache}}$ $\color{#D6DEE3}{\textsf{zu}}$ $\color{#FD5959}{\textsf{FUP}}$ $\color{#D6DEE3}{\textsf{und bestätigen mit}}$ $\color{#FD5959}{\textsf{OK}}$.</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 2.1.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Der Baustein}}$ $\color{#FD5959}{\textsf{FC1}}$ $\color{#D6DEE3}{\textsf{sollte nun im Fenster auftauchen.}}$</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 3.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Nun öffnen wir den}}$ $\color{#FD5959}{\textsf{OB1}}$ $\color{#D6DEE3}{\textsf{mit einem}}$ $\color{#FD5959}{\textsf{Doppelklick}}$ $\color{#D6DEE3}{\textsf{.}}$</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 4.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Es öffnet sich folgendes Fenster.}}$<br>
            $\color{#D6DEE3}{\textsf{In das}}$ $\color{#FD5959}{\textsf{Netzwerk 1}}$ $\color{#D6DEE3}{\textsf{schreiben wir nun}}$ $\color{#FD5959}{\textsf{CALL FC1}}$ $\color{#D6DEE3}{\textsf{und bestätigen dies mit}}$ $\color{#FD5959}{\textsf{ENTER}}$ $\color{#D6DEE3}{\textsf{.}}$</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
    <h3>Schritt 5.)</h3>
    <figure>
        <blockquote>
            <p>$\color{#D6DEE3}{\textsf{Anschließend}}$ $\color{#FD5959}{\textsf{speichern}}$ $\color{#D6DEE3}{\textsf{wir den Baustein und}}$ $\color{#FD5959}{\textsf{schließen}}$ $\color{#D6DEE3}{\textsf{das Fenster.}}$</p>
            <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/PLACEHOLDER.png" alt="image" width="600" height="auto" alt="(Bild: Installationsassistent)">
        </blockquote>
    </figure>
    <br>
</details>

<details>
    <summary><h2>4. Aufgaben</h2></summary>
    <details>
        <summary><h3>4.1. RS-Flip Flop</h3></summary>
        <p>Aufgabe.</p>
    </details>
    <details>
        <summary><h3>4.2. Generator mit 4 Motoren</h3></summary>
        <p>Aufgabe.</p>
    </details>
    <details>
        <summary><h3>4.3. Torantrieb</h3></summary>
        <figure>
            <blockquote>
                <p>$\color{#D6DEE3}{\textsf{Es soll ein SPS-Programm für einen Torantrieb geschrieben werden.}}$<br>
                $\color{#D6DEE3}{\textsf{Folgende Funktionsweise ist dabei zu beachten:}}$<br>
                <br>
                $\color{#D6DEE3}{\textsf{1. Das Schütz Q1 hat dann 1-Signal, solange S1 gedrückt ist, S2 nicht und S3 ein 1-Signal liefert.}}$<br>
                $\color{#D6DEE3}{\textsf{2. Das Schütz Q2 hat dann 1-Signal, solange S2 gedrückt ist, S1 nicht und S4 ein 1-Signal liefert.}}$<br>
                $\color{#D6DEE3}{\textsf{3. Erweiterung: Es sollen 2 Anzeigen den Zustand des Tores anzeigen}}$<br>
                $\color{#D6DEE3}{\textsf{&emsp;&emsp;A6.3 - Tor ist auf}}$<br>
                $\color{#D6DEE3}{\textsf{&emsp;&emsp;A6.4 - Tor ist zu}}$<br>
                <br>
                $\color{#D6DEE3}{\textsf{Entwickeln Sie das SPS-Programm unter Berücksichtigung o. a. Bedingungen und testen Sie es im OB1!}}$<br>
                <br></p>
                <img src="https://raw.githubusercontent.com/nitrotorben/Meisterschule/main/bilder/aufg1_bilder_1.png" alt="image" width="1200" height="auto" alt="(Bild: Technologieschema)">
            </blockquote>
        </figure>
    </details>
    <details>
        <summary><h3>4.4. Kläranlage mit 2 Pumpen und Schieber</summary>
            <p>Aufgabe.</p>
    </details>
</details>
