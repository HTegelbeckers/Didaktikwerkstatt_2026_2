<!--
author:   Dr. Hannes Tegelbeckers / ITVET – Otto-von-Guericke-Universität Magdeburg
email:    itvet@ovgu.de
version:  1.0.0
language: de
narrator: German Female

comment:  Kompetenzorientierter Unterricht mit dem mBot –
          Lehrerfortbildungsmodul im Rahmen des UNESCO IKT-Kompetenzrahmens für Lehrkräfte (ICT-CFT)
          Zielgruppe: Lehrende im Sekundar- und Gymnasialbereich ohne oder mit geringer Programmiererfahrung

logo: https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Makeblock_mBot.jpg/640px-Makeblock_mBot.jpg

link: https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&display=swap

@style
body, .lia-slide {
  font-family: 'Nunito', sans-serif;
}
.info-box {
  background: #eef6fb;
  border-left: 5px solid #1a73e8;
  padding: 14px 18px;
  border-radius: 6px;
  margin: 12px 0;
}
.success-box {
  background: #e8f5e9;
  border-left: 5px solid #34a853;
  padding: 14px 18px;
  border-radius: 6px;
  margin: 12px 0;
}
.warning-box {
  background: #fff8e1;
  border-left: 5px solid #f9a825;
  padding: 14px 18px;
  border-radius: 6px;
  margin: 12px 0;
}
.tip-box {
  background: #fce4ec;
  border-left: 5px solid #e91e63;
  padding: 14px 18px;
  border-radius: 6px;
  margin: 12px 0;
}
.step-box {
  background: #f3e5f5;
  border-left: 5px solid #9c27b0;
  padding: 14px 18px;
  border-radius: 6px;
  margin: 10px 0;
}
@end
-->

# 🤖 Kompetenzorientierter Unterricht mit dem mBot

### Lehrerfortbildungsmodul | UNESCO IKT-Kompetenzrahmen für Lehrkräfte (ICT-CFT)

---

<div class="info-box">

📌 **Über dieses Modul**

Dieses Fortbildungsmodul richtet sich an Lehrende im Sekundar- und Gymnasialbereich, die **keine oder wenig Vorkenntnisse** in Programmierung und Robotik mitbringen. Es zeigt schrittweise, wie der **mBot** als pädagogisches Werkzeug genutzt werden kann – nicht als Selbstzweck, sondern als Katalysator für kompetenzorientiertes, fächerübergreifendes Lernen.

</div>

---

**Kursüberblick**

| | |
|---|---|
| 🎯 **Zielgruppe** | Lehrende im Sekundar- und Gymnasialbereich |
| 📚 **Vorkenntnisse** | Keine Programmiererfahrung erforderlich |
| ⏱️ **Gesamtdauer** | ca. 6–8 Stunden (4 Module à 90–120 Min.) |
| 🤖 **Werkzeug** | mBot (Makeblock) + mBlock-Software (kostenlos) |
| 📋 **Rahmenwerk** | UNESCO ICT-CFT (Erwerbs-, Vertiefungs- und Gestaltungsebene) |
| 🌐 **Format** | Präsenz + digitale Selbstlernphasen (Blended Learning) |

---

**Modulstruktur im Überblick**

| Modul | Titel | ICT-CFT-Ebene |
|---|---|---|
| **1** | Was ist der mBot? – Einstieg ohne Vorkenntnisse | Erwerbsebene |
| **2** | Zusammenbau & erste Schritte | Erwerbsebene |
| **3** | Vom Klick zum Konzept – Programmieren mit mBlock | Vertiefungsebene |
| **4** | Transfer in den Fachunterricht & fächerübergreifend | Gestaltungsebene |

---

> 💡 **Leitgedanke:**
> *Der mBot ist kein Spielzeug und kein reines MINT-Werkzeug. Er ist ein physisches Medium, das abstrakte Konzepte greifbar macht – in Mathematik, Physik, Ethik, Sprache und weit darüber hinaus.*

---

## 🎯 Übergreifende Lernziele der Fortbildung

Nach Abschluss dieser Fortbildung sind die Teilnehmenden in der Lage:

- [[x]] Den mBot als pädagogisches Werkzeug im eigenen Fachunterricht zu identifizieren und einzusetzen
- [[x]] Grundlegende Programmierprinzipien (Sequenz, Bedingung, Schleifen) mit mBlock anzuwenden
- [[x]] Unterrichtsszenarien zu entwickeln, die über die bloße Anwendung von Technologie hinausgehen (*Transformationsebene*)
- [[x]] Kompetenzorientierte Aufgabenstellungen für heterogene Lerngruppen zu entwerfen
- [[x]] Den mBot mit dem UNESCO IKT-Kompetenzrahmen für Lehrkräfte (ICT-CFT) zu verknüpfen
- [[x]] Ethische Fragen rund um Algorithmen und KI im Unterricht zu thematisieren

---

## 📌 Modul 1 – Was ist der mBot? Einstieg ohne Vorkenntnisse

> **ICT-CFT-Ebene:** Erwerbsebene · Aspekt 4: Anwendung digitaler Kompetenzen
>
> **Dauer:** ca. 90 Minuten

---

### Lernziele Modul 1

Nach dieser Einheit können die Teilnehmenden:

1. Den mBot als physisches System mit Eingabe–Verarbeitung–Ausgabe beschreiben
2. Erklären, warum Robotik kein MINT-exklusives Thema ist
3. Mindestens **zwei eigene Fachbezüge** zum mBot benennen
4. Die drei Ebenen des UNESCO ICT-CFT unterscheiden: *Anwendung → Vertiefung → Gestaltung*

---

### 1.1 Warum dieser Roboter – und warum ich?

<div class="warning-box">

🤔 **Reflexion zum Einstieg (5 Minuten)**

Bitte nehmen Sie sich kurz Zeit und notieren Sie:

- *Welches Bild haben Sie vor Augen, wenn Sie das Wort „Robotik im Unterricht" hören?*
- *Für welches Fach halten Sie Robotik am wenigsten geeignet? Warum?*

*(Diese Fragen werden am Ende von Modul 1 erneut gestellt – und die Antworten überraschend oft revidiert.)*

</div>

---

**Das Missverständnis: Robotik ist kein MINT-Thema**

Eine verbreitete Fehlannahme ist, dass Robotik ausschließlich dem Informatikunterricht oder den MINT-Fächern vorbehalten ist. Das UNESCO ICT-Kompetenzrahmenwerk für Lehrkräfte (ICT-CFT) widerspricht dieser Engführung ausdrücklich: Digitale Kompetenzen gelten als **fächerübergreifende Querschnittskompetenz**, die in allen Lernbereichen entwickelt werden kann und soll (UNESCO, 2018).

Der mBot bietet dabei besondere Stärken:

- **Niedrige Zugangsschwelle:** Blockbasierte Programmierung (mBlock/Scratch) erfordert keine Syntax-Kenntnisse
- **Physische Rückkopplung:** Lernende sehen sofortige, reale Konsequenzen ihres Codes
- **Günstiger Einstiegspreis:** Ca. 35–55 € pro Gerät, Open-Source-Software
- **Fächerbrücke:** Ein einziger Roboter eröffnet Zugänge zu Mathematik, Physik, Ethik, Sprache, Sozialkunde und mehr

---

### 1.2 Der mBot als System: Eingabe – Verarbeitung – Ausgabe

> Alle technischen Systeme – von der Ampelanlage bis zur künstlichen Intelligenz – folgen demselben Grundprinzip. Der mBot macht dieses Prinzip **sichtbar und begreifbar**.

```ascii
  +--------------------+     +----------------------+     +-------------------+
  |     EINGABE        | --> |    VERARBEITUNG       | --> |      AUSGABE      |
  | • Ultraschallsensor|     | • mBlock-Programm    |     | • Motoren         |
  | • Lichtsensor      |     | • Wenn-Dann-Logik    |     | • LEDs            |
  | • IR-Sensor        |     | • Schleifen          |     | • Summerton       |
  | • Fernbedienung    |     | • Variablen          |     | • Display         |
  +--------------------+     +----------------------+     +-------------------+
```

<div class="info-box">

🔑 **Kerngedanke für Lehrende:**

Diese Eingabe–Verarbeitung–Ausgabe-Struktur ist identisch mit der Funktionsweise von KI-Systemen (Sensordaten → Algorithmus → Entscheidung). Der mBot ist damit nicht nur ein Programmierwerkzeug, sondern ein **physisches Modell für KI-Grundkonzepte** – relevant für Informatik, Ethik und Medienkunde.

</div>

---

### 1.3 Der UNESCO ICT-Kompetenzrahmen: Drei Ebenen im Überblick

Das ICT-CFT der UNESCO (Version 3, 2018) unterscheidet drei progressive Kompetenzebenen für Lehrende:

| Ebene | Kernidee | mBot-Beispiel |
|---|---|---|
| 🖥️ **Erwerb** | Lehrende nutzen digitale Werkzeuge zur Unterstützung traditionellen Unterrichts | Demo: Lehrperson zeigt mBot-Fahrt; Lernende schauen zu |
| 🔗 **Vertiefung** | Digitale Medien fest in Lehr-Lern-Prozesse eingebunden; Förderung höherer Denktätigkeiten | Lernende programmieren Sensorreaktion als Lösung eines strukturierten Problems |
| 🚀 **Gestaltung** | Digitale Kompetenzen ermöglichen völlig neue Lernformen, die ohne Technologie unmöglich wären | Teams entwickeln mBot-Lösung für reales Szenario; Lehrende als Coach |

<div class="success-box">

✅ **Ziel dieser Fortbildung:** Lehrende sollen die Gestaltungsebene nicht nur kennen, sondern **selbst erleben** – und mindestens eine Unterrichtseinheit auf diesem Niveau planen.

</div>

---

### 1.4 Fächerübergreifende Einsatzmöglichkeiten – Erste Ideensammlung

> Welche Fachbezüge sehen Sie? Ergänzen Sie die Tabelle gedanklich um Ihr eigenes Fach.

| Fach | mBot-Anknüpfungspunkt | Kompetenzbereich |
|---|---|---|
| **Mathematik** | Koordinatensystem, Winkel, Proportionen beim Navigieren | Räumliches Denken, Modellierung |
| **Physik** | Messung von Abstand, Licht, Geschwindigkeit | Experimentelles Arbeiten, Messunsicherheit |
| **Ethik/Philosophie** | Bias im Lichtsensor – was ist gerechte Technologie? | Kritisches Denken, Verantwortung |
| **Sprache/Deutsch** | Technische Dokumentation, Bedienungsanleitung schreiben | Fachsprache, Textproduktion |
| **Sozialkunde** | Automatisierung und Arbeitswelt, KI und Gesellschaft | Medienkompetenz, gesellschaftliche Teilhabe |
| **Kunst/Design** | Parcours gestalten, Roboter-Performance choreografieren | Kreativität, ästhetisches Urteilen |
| **Sport** | mBot als Staffelläufer – Datenlogging, Teamstrategie | Kooperation, Analyse |

---

### ✔️ Wissenscheck Modul 1

**Frage 1:** Welches Grundprinzip liegt sowohl dem mBot als auch KI-Systemen zugrunde?

[( )] Lernstil–Ergebnis–Bewertung
[(x)] Eingabe–Verarbeitung–Ausgabe
[( )] Hardware–Software–Netzwerk
[( )] Sensor–Kalibrierung–Druckausgabe

---

**Frage 2:** Auf welcher ICT-CFT-Ebene befinden sich Lehrende, wenn sie einen mBot lediglich vorführen, ohne dass Lernende selbst aktiv werden?

[( )] Gestaltungsebene
[( )] Vertiefungsebene
[(x)] Erwerbsebene
[( )] Transferebene

---

**Frage 3:** Welche Aussage über den Einsatz von Robotik im Unterricht ist korrekt?

[( )] Robotik eignet sich ausschließlich für MINT-Fächer
[( )] Robotik setzt zwingend Python-Kenntnisse voraus
[(x)] Robotik kann als fächerübergreifende Querschnittskompetenz in nahezu allen Fächern eingesetzt werden
[( )] Robotik erfordert immer spezielle IT-Infrastruktur

---

### 📚 Ressourcen für Modul 1

- [UNESCO ICT-Kompetenzrahmen für Lehrkräfte (ICT-CFT v3)](https://unesdoc.unesco.org/ark:/48223/pf0000265721)
- [mBot – Offizielle Produktseite (Makeblock)](https://www.makeblock.com/mbot)
- [mBlock – Kostenlose Programmiersoftware](https://mblock.makeblock.com)
- [AI4K12 – Fünf große Ideen der KI (englisch)](https://ai4k12.org)

---

## 🔧 Modul 2 – Zusammenbau & erste Schritte

> **ICT-CFT-Ebene:** Erwerbsebene · Aspekt 4.a: Hardware kennen und anwenden
>
> **Dauer:** ca. 90 Minuten

---

### Lernziele Modul 2

Nach dieser Einheit können die Teilnehmenden:

1. Den mBot eigenständig und sicher zusammenbauen
2. Die Hauptkomponenten benennen und ihre Funktion erklären
3. Die mBlock-Software installieren und mit dem mBot verbinden
4. Ein erstes Programm (Geradeausfahren, Stopp) erstellen und ausführen

---

### 2.1 Komponenten des mBot – Überblick

<div class="info-box">

📦 **Lieferumfang (mBot Ranger / Standard)**

Vor dem Zusammenbau sollten alle Teile identifiziert und gezählt werden:

| Bauteil | Anzahl | Funktion |
|---|---|---|
| Hauptplatine (mCore) | 1 | Steuerung, Bluetooth/WiFi |
| Chassis (Grundplatte) | 1 | Strukturelle Basis |
| DC-Motoren | 2 | Antrieb links/rechts |
| Räder (groß) | 2 | Fahren |
| Stützrad (Kugel) | 1 | Balance vorne |
| Ultraschall-Sensor | 1 | Abstandsmessung |
| Linienfolge-Sensor | 1 | Schwarze Linie erkennen |
| RGB-LEDs | 2 | Lichtsignale |
| Batteriefach (AA) | 1 | Stromversorgung |
| Schrauben & Muttern | Set | Verbindungselemente |
| Schraubenzieher | 1 | Im Lieferumfang |
| USB-Kabel (Micro-USB) | 1 | PC-Verbindung & Laden |

</div>

---

### 2.2 Schritt-für-Schritt-Zusammenbau

<div class="step-box">

**🔩 Schritt 1 – Motoren befestigen** *(ca. 5 Minuten)*

1. Legen Sie das Chassis (Grundplatte) mit der bedruckten Seite nach oben vor sich
2. Positionieren Sie den linken Motor auf der linken Seite der Grundplatte – die Kabelöffnung zeigt nach innen
3. Befestigen Sie den Motor mit **2 Schrauben und 2 Muttern** (Kreuzschlitzschrauben)
4. Wiederholen Sie den Vorgang auf der rechten Seite
5. ✅ **Kontrolle:** Beide Motoren sitzen fest und zeigen in die gleiche Richtung

</div>

<div class="step-box">

**🔩 Schritt 2 – Räder montieren** *(ca. 3 Minuten)*

1. Stecken Sie das linke Rad auf die Motorwelle (links) – es rastet mit leichtem Druck ein
2. Stecken Sie das rechte Rad auf die rechte Motorwelle
3. ✅ **Kontrolle:** Drehen Sie beide Räder von Hand – sie sollten sich frei und gleichmäßig drehen

</div>

<div class="step-box">

**🔩 Schritt 3 – Stützrad (Kugelrolle) befestigen** *(ca. 3 Minuten)*

1. Schrauben Sie die Kugelrolle (Stützrad) an die vorgesehene Öffnung an der **Vorderseite** des Chassis
2. Verwenden Sie **2 Schrauben**
3. ✅ **Kontrolle:** Die Kugel sollte sich in alle Richtungen frei drollen können

</div>

<div class="step-box">

**🔩 Schritt 4 – Hauptplatine (mCore) montieren** *(ca. 5 Minuten)*

1. Positionieren Sie die mCore-Platine mittig auf dem Chassis (USB-Anschluss zeigt nach vorne/oben)
2. Befestigen Sie die Platine mit **4 Schrauben und Abstandshaltern**
3. ✅ **Kontrolle:** Die Platine sitzt stabil; die Motoranschlüsse (M1, M2) sind von oben zugänglich

</div>

<div class="step-box">

**🔩 Schritt 5 – Motorkabel verbinden** *(ca. 3 Minuten)*

1. Stecken Sie das **linke Motorkabel** in die Buchse **M1** auf der Platine
2. Stecken Sie das **rechte Motorkabel** in die Buchse **M2**
3. ⚠️ **Achtung:** Die Stecker sind kodiert – sie passen nur in der richtigen Orientierung

</div>

<div class="step-box">

**🔩 Schritt 6 – Ultraschall-Sensor befestigen** *(ca. 3 Minuten)*

1. Befestigen Sie den Ultraschall-Sensor an der **Vorderseite** des Chassis (die zwei „Augen" zeigen nach vorne)
2. Verbinden Sie das Kabel mit dem **Port 3** auf der mCore-Platine
3. ✅ **Kontrolle:** Die Ausrichtung der Sensoraugen entspricht der Fahrtrichtung

</div>

<div class="step-box">

**🔩 Schritt 7 – Linienfolge-Sensor befestigen** *(ca. 3 Minuten)*

1. Befestigen Sie den Linienfolge-Sensor **unten** an der Vorderseite des Chassis (die Infrarot-LEDs zeigen nach unten zum Boden)
2. Verbinden Sie das Kabel mit **Port 2** auf der mCore-Platine
3. ✅ **Kontrolle:** Der Sensor hat ca. 5–10 mm Abstand zum Boden

</div>

<div class="step-box">

**🔩 Schritt 8 – Batteriefach einsetzen & Kabel verlegen** *(ca. 5 Minuten)*

1. Legen Sie 4× AA-Batterien ins Batteriefach (Polarität beachten)
2. Befestigen Sie das Batteriefach auf der **Unterseite** oder dem hinteren Teil des Chassis
3. Verbinden Sie das Stromkabel mit der Platine
4. Verlegen Sie alle losen Kabel ordentlich (ggf. mit Kabelbindern aus dem Lieferumfang)
5. ✅ **Abschlusskontrolle:** Kein Kabel berührt ein Rad; alle Stecker sitzen fest

</div>

<div class="success-box">

🎉 **Zusammenbau abgeschlossen!**

Schalten Sie den mBot ein (Schiebeschalter an der Platine). Die LEDs leuchten blau und ein Startton ertönt – der mBot ist betriebsbereit.

</div>

---

### 2.3 Software-Einrichtung: mBlock

<div class="info-box">

💻 **mBlock installieren und verbinden**

**Schritt 1:** Besuchen Sie [mblock.makeblock.com](https://mblock.makeblock.com) und laden Sie die Software für Ihr Betriebssystem herunter (Windows / macOS / Linux)

**Schritt 2:** Installieren Sie mBlock und starten Sie die Anwendung

**Schritt 3:** Verbinden Sie den mBot via **USB-Kabel** mit dem Computer

**Schritt 4:** In mBlock: *Gerät hinzufügen → mBot → USB verbinden*

**Schritt 5:** Klicken Sie auf „**Verbinden**" – die Statusanzeige wechselt auf grün

**Alternative:** Bluetooth-Verbindung (Bluetooth-Modul muss eingesteckt sein, Treiber ggf. notwendig)

</div>

---

### 2.4 Erstes Programm: Bewege dich!

Das erste Programm ist bewusst einfach gehalten – es geht ums **Erleben**, nicht um Perfektion.

```
[Wenn Startflagge geklickt]
    [Linken Motor mit Geschwindigkeit 100 vorwärts]
    [Rechten Motor mit Geschwindigkeit 100 vorwärts]
    [Warte 2 Sekunden]
    [Alle Motoren stoppen]
```

<div class="tip-box">

💡 **Didaktischer Hinweis für Lehrende**

Dieser erste Schritt ist bewusst **niedrigschwellig** gestaltet. Erfahrungen zeigen, dass auch Teilnehmende ohne jede Vorerfahrung bereits nach 5 Minuten ein funktionierendes Programm ausführen können. Dieses Erfolgserlebnis ist pädagogisch zentral – es verändert die Haltung gegenüber Technologie.

Empfehlung: Lassen Sie die Teilnehmenden **selbst entdecken**, was passiert, wenn unterschiedliche Geschwindigkeitswerte eingestellt werden (z. B. links 80, rechts 100). Die Frage „Warum dreht er sich?" öffnet direkt den Weg zu Differenzierung, Algorithmen und mathematischem Denken.

</div>

---

### ✔️ Wissenscheck Modul 2

**Frage 4:** An welchen Port wird der Ultraschall-Sensor des mBot angeschlossen?

[( )] Port 1
[( )] Port 2
[(x)] Port 3
[( )] Port M1

---

**Frage 5:** Was passiert mit dem mBot, wenn der linke Motor auf Geschwindigkeit 80 und der rechte Motor auf Geschwindigkeit 100 eingestellt wird?

[( )] Er fährt geradeaus, aber langsamer
[(x)] Er dreht sich nach links (nach innen zum langsameren Rad)
[( )] Er stoppt sofort
[( )] Er fährt rückwärts

---

**Frage 6:** Was ist der didaktische Mehrwert des physischen Zusammenbaus (im Vergleich zu einem virtuellen Simulator)?

[( )] Der Zusammenbau ist schneller als ein Simulator
[( )] Virtuelle Simulatoren sind für Lernende zu komplex
[(x)] Physische Handlungserfahrung schafft ein tieferes konzeptuelles Verständnis von Systemkomponenten und ihrer Funktion
[( )] Simulatoren können Sensordaten nicht korrekt darstellen

---

## 💡 Modul 3 – Vom Klick zum Konzept: Programmieren mit mBlock

> **ICT-CFT-Ebene:** Vertiefungsebene · Aspekt 4.c/f: Lernmaterialien gestalten & kollaborativ arbeiten
>
> **Dauer:** ca. 120 Minuten

---

### Lernziele Modul 3

Nach dieser Einheit können die Teilnehmenden:

1. Die drei Grundstrukturen der Programmierung (Sequenz, Bedingung, Schleife) in mBlock umsetzen
2. Sensorwerte lesen und für Entscheidungen verwenden
3. Einen Linienfolge-Algorithmus entwickeln und iterativ verbessern
4. Den Begriff „Algorithmus" für Lernende ihres Faches verständlich erklären

---

### 3.1 Grundstrukturen der Programmierung am mBot

<div class="info-box">

🔑 **Die drei universellen Bausteine**

Diese drei Strukturen bilden die Grundlage **jedes** Computerprogramms – von mBlock bis zur KI:

</div>

**Struktur 1: Sequenz** *(Abfolge)*

Eine Reihe von Befehlen wird der Reihe nach ausgeführt.

```
[Warte 1 Sekunde]
[Fahre vorwärts]
[Warte 2 Sekunden]
[Stopp]
[Warte 1 Sekunde]
[Fahre rückwärts]
[Warte 1 Sekunde]
[Stopp]
```

---

**Struktur 2: Bedingung** *(Wenn-Dann-Sonst)*

Das Programm trifft eine Entscheidung abhängig von einem Sensorwert.

```
[Wiederhole fortlaufend]
    [Wenn Ultraschall-Abstand < 15 cm]
        [Stopp]
        [Ton abspielen: Alarm]
    [Sonst]
        [Fahre vorwärts mit Geschwindigkeit 80]
```

---

**Struktur 3: Schleife** *(Wiederholung)*

Befehle werden wiederholt ausgeführt – entweder eine bestimmte Anzahl von Malen oder solange eine Bedingung gilt.

```
[Wiederhole 4 mal]
    [Fahre vorwärts 1 Sekunde]
    [Drehe rechts 90°]
```

<div class="success-box">

🔁 **Fächerverbindung Mathematik:**

Das Quadrat-Programm oben macht ein abstraktes geometrisches Konzept physisch erfahrbar: Ein Quadrat entsteht durch **4 × (Geradeaus + 90°-Drehung)**. Lernende erleben, dass mathematische Regelmäßigkeit in Bewegung übertragbar ist.

</div>

---

### 3.2 Praxisaufgabe: Der Linienfolger

> Der Linienfolger ist die „klassische" mBot-Aufgabe – und eine direkte Analogie zu maschinellem Lernen.

**Das Ziel:** Der mBot soll einer schwarzen Linie auf weißem Untergrund folgen, ohne sie zu verlassen.

**Der Algorithmus (vereinfacht):**

```
[Wiederhole fortlaufend]
    [Lese Linienfolger-Sensor]
    
    [Wenn beide Sensoren auf Schwarz]
        → Fahre geradeaus
    
    [Wenn linker Sensor auf Schwarz, rechter auf Weiß]
        → Drehe leicht nach links
    
    [Wenn rechter Sensor auf Schwarz, linker auf Weiß]
        → Drehe leicht nach rechts
    
    [Wenn beide Sensoren auf Weiß]
        → Stopp (Linie verloren)
```

<div class="tip-box">

💡 **Didaktische Reflexion: Analogie zu KI**

Der Linienfolger-Algorithmus ist eine Wenn-Dann-Entscheidungslogik – regelbasierte KI. Er unterscheidet sich von maschinellem Lernen dadurch, dass die Regeln **explizit programmiert** wurden, anstatt aus Daten gelernt zu werden. Diese Unterscheidung ist für den Ethikunterricht und für Medienkunde hochrelevant: *Wer entscheidet, nach welchen Regeln eine KI handelt?*

</div>

---

### 3.3 Iteration als Lernprinzip

In der Softwareentwicklung und im wissenschaftlichen Arbeiten ist **iteratives Verbessern** eine Kernkompetenz. Der mBot macht dieses Prinzip erlebbar:

| Iteration | Beobachtung | Anpassung |
|---|---|---|
| **1. Versuch** | mBot verlässt die Linie bei Kurven | Reaktionsgeschwindigkeit erhöhen |
| **2. Versuch** | mBot oszilliert stark (zittert) | Korrekturdrehung verringern |
| **3. Versuch** | Stabile Kurvenfahrt | Geschwindigkeit erhöhen |
| **4. Versuch** | Optimales Ergebnis für diesen Parcours | Dokumentation & Reflexion |

<div class="info-box">

📐 **Kompetenzorientierung:**

Dieser Prozess entspricht dem **wissenschaftlichen Denken** (Hypothese → Test → Auswertung → Anpassung) und dem **agilen Projektmanagement** (Sprint → Review → Retrospektive). Lehrende aus Naturwissenschaften, aber auch aus Sprach- und Geisteswissenschaften können dieses Muster für ihren Fachunterricht nutzen.

</div>

---

### 3.4 Reflexionsfragen für Lehrende

> Nehmen Sie sich 10 Minuten für eine persönliche Reflexion (Einzelarbeit oder Partnerarbeit):

1. **Inwiefern ähnelt das Debugging eines mBot-Programms dem Korrigieren eines Aufsatzes oder dem Verbessern eines Experiments?** Welche Haltung gegenüber Fehlern vermitteln beide Prozesse?

2. **Welchen Lernendentypus** in Ihrer Klasse stellen Sie sich vor, der beim mBot-Programmieren **überraschend aufblühen** könnte – und warum könnte das der Schule bisher verborgen geblieben sein?

3. **Wie würden Sie den Begriff „Algorithmus" einem 14-jährigen Schüler ohne Computer erklären?** Nutzen Sie dazu ein Alltagsbeispiel aus Ihrem Fach (z. B. Rezept, Rechtschreibregel, historische Methode).

---

### ✔️ Wissenscheck Modul 3

**Frage 7:** Welche der folgenden Programmierstrukturen liegt vor, wenn ein mBot-Programm den Sensorwert prüft und je nach Ergebnis unterschiedliche Befehle ausführt?

[( )] Sequenz
[(x)] Bedingte Anweisung (Selektion)
[( )] Schleife (Iteration)
[( )] Funktion (Abstraktion)

---

**Frage 8:** Was versteht man im Kontext des mBot-Linienfolgers unter „Iteration"?

[( )] Das einmalige Ausführen eines vollständigen Programms
[( )] Das Umschreiben des Programms in eine andere Programmiersprache
[(x)] Das zyklische Testen, Beobachten und Verbessern des Programms auf Basis von Erfahrungen
[( )] Das gleichzeitige Ausführen mehrerer Programme

---

**Frage 9:** Worin unterscheidet sich die regelbasierte KI (wie der mBot-Linienfolger) vom maschinellen Lernen?

[(x)] Beim regelbasierten Ansatz werden Entscheidungsregeln explizit vom Menschen programmiert; beim ML werden Muster aus Daten gelernt
[( )] Regelbasierte KI ist immer genauer als maschinelles Lernen
[( )] Maschinelles Lernen benötigt keine Daten
[( )] Der mBot kann selbst Daten sammeln und sich eigenständig weiterentwickeln

---

## 🚀 Modul 4 – Transfer in den Fachunterricht & fächerübergreifendes Lernen

> **ICT-CFT-Ebene:** Gestaltungsebene · Kompetenz 3.2: KI-Grundlagen und Lehrpraxis
>
> **Dauer:** ca. 120 Minuten

---

### Lernziele Modul 4

Nach dieser Einheit können die Teilnehmenden:

1. Eine Unterrichtseinheit auf Transformationsniveau (Gestaltungsebene) für das eigene Fach planen
2. Kollaborative Lernszenarien mit dem mBot gestalten
3. Ethische Dimensionen des Algorithmus-Einsatzes im Unterricht thematisieren
4. Eine kompetenzorientierte Aufgabe im Format des UNESCO ICT-CFT formulieren

---

### 4.1 Vom Anwenden zum Gestalten – Die Transformationsebene

> Die Gestaltungsebene ist nicht mehr Technologie *im* Unterricht – es ist Technologie als *Ermöglichungsstruktur* für fundamental neues Lernen.

**Was bedeutet „Transformation" konkret?**

Stellen Sie sich folgende Prüffrage:

<div class="success-box">

✅ **Transformations-Test:**

*Könnte diese Lerneinheit genauso gut ohne den mBot und ohne digitale Werkzeuge stattfinden?*

**Wenn die Antwort „Ja" ist** → Sie befinden sich auf der Anwendungsebene.

**Wenn die Antwort „Nein" ist** → Sie haben die Transformationsebene erreicht.

</div>

---

**Vergleich der drei Ebenen am Beispiel „Linienverfolgung":**

| Ebene | Unterrichtsgestaltung |
|---|---|
| **Anwendung** | Lehrkraft demonstriert Linienfolger; Lernende schauen zu und beschreiben |
| **Vertiefung** | Lernende programmieren den Linienfolger nach einem strukturierten Skript und vergleichen ihre Lösungen |
| **Gestaltung** | Teams entwickeln den **optimalen** Linienfolger für einen selbst gestalteten Parcours, der eine reale Herausforderung simuliert (z. B. autonome Lieferroboter im Krankenhaus); sie präsentieren, vergleichen und bewerten Lösungen gegenseitig – Lehrkraft ist Coach |

---

### 4.2 Szenariobasiertes Lernen: Design-Vorlagen für Unterrichtseinheiten

<div class="info-box">

🗂️ **Vorlage: Transformations-Unterrichtseinheit mit dem mBot**

Nutzen Sie diese Struktur für Ihre eigene Einheit:

</div>

**① Problemszenario definieren**

Beschreiben Sie ein reales oder realistisches Problem, das der mBot lösen soll – *nicht* nur „fahren lassen".

*Beispiel Mathematik:* „Der mBot muss ein exaktes Quadrat mit 40 cm Seitenlänge abfahren. Welche Parameter im Code müssen wie angepasst werden? Dokumentiert eure Erkenntnisse in einer Formel."

*Beispiel Ethik:* „Der mBot-Lichtsensor reagiert auf verschiedene Untergründe unterschiedlich. Testet systematisch, bei welchen Farben oder Helligkeiten er versagt. Was bedeutet das für KI-Systeme in der echten Welt (z. B. Gesichtserkennung)?"

*Beispiel Sprache/Deutsch:* „Schreibt eine präzise Bedienungsanleitung für euren mBot-Algorithmus, die ein Mitschüler ohne Vorerfahrung verstehen und reproduzieren kann."

---

**② Kollaborative Rollen vergeben**

| Rolle | Aufgabe |
|---|---|
| 🗺️ Navigator:in | Plant die Logik, skizziert den Algorithmus |
| 💻 Programmierer:in | Setzt den Plan in mBlock um |
| 🔬 Tester:in | Führt Testläufe durch, dokumentiert Fehler |
| 📝 Dokumentar:in | Hält Ergebnisse fest, bereitet Präsentation vor |

---

**③ Iteration und Reflexion einbauen**

- Mindestens **zwei Verbesserungszyklen** einplanen
- Zwischenreflexion nach jedem Zyklus: *Was hat funktioniert? Was nicht? Warum?*
- Abschluss: Peer-Feedback zwischen Gruppen

---

**④ Transferfrage als Abschluss**

Jede Einheit endet mit einer Transferfrage, die den mBot-Kontext verlässt:

*Beispiel:* „Wie würdet ihr das, was ihr über Algorithmen gelernt habt, auf die Entscheidungsprozesse von Streamingdiensten anwenden? Wer profitiert von solchen Algorithmen – und wer nicht?"

---

### 4.3 Kompetenzorientierung: Was wird eigentlich gemessen?

Der Einsatz des mBot zielt auf **transferierbare Kompetenzen**, nicht auf das Wissen über den Roboter selbst. Folgende Kompetenzbereiche werden durch mBot-Szenarien auf Gestaltungsebene gefördert:

| Kompetenzbereich | Konkrete Ausprägung im mBot-Kontext |
|---|---|
| **Problemlösen** | Komplexe Aufgabe in lösbare Teilprobleme zerlegen |
| **Computational Thinking** | Algorithmen denken, Muster erkennen, abstrahieren |
| **Kollaboration** | Rollen klären, Arbeit aufteilen, Ergebnisse zusammenführen |
| **Kommunikation** | Technische Lösungen für Fachfremde verständlich machen |
| **Kritisches Denken** | Algorithmen hinterfragen, Bias und Fehlverhalten erkennen |
| **Kreativität** | Eigene Szenarien entwickeln, Probleme neu definieren |
| **Metakognition** | Den eigenen Lernprozess beobachten und steuern |

<div class="tip-box">

💡 **Hinweis zur Bewertung:**

Kompetenzorientierte Leistungsbeurteilung im mBot-Kontext kann über **Lerntagebücher, Portfolios, Code-Dokumentation oder Peer-Präsentationen** erfolgen – nicht über Multiple-Choice-Tests. Das Produkt ist der Prozess.

</div>

---

### 4.4 Ethik by Design: KI-Kritik im Unterricht

Eine der stärksten Lernmöglichkeiten des mBot liegt in seiner Fehleranfälligkeit. Der Lichtsensor des mBot erkennt Linien auf Basis von Helligkeitswerten – und versagt unter bestimmten Bedingungen (ungünstige Beleuchtung, farbige Untergründe, helle Linien auf hellem Grund).

**Unterrichtsaktivität: Das Bias-Audit**

Lernende testen den Linienfolger systematisch auf verschiedenen Untergründen:

| Testbedingung | Erwartetes Ergebnis | Tatsächliches Ergebnis |
|---|---|---|
| Schwarze Linie auf Weiß | Linienfolgen stabil | ??? |
| Schwarze Linie auf Grau | Linienfolgen stabil | ??? |
| Schwarze Linie bei Schattenwurf | Linienfolgen stabil | ??? |
| Dunkelblaue Linie auf Weiß | Linienfolgen stabil | ??? |

**Transferfragen für den Unterricht:**

- Welche gesellschaftlichen Gruppen könnten von einem fehlerhaft kalibrierten KI-System benachteiligt werden?
- Wer ist verantwortlich, wenn ein Algorithmus diskriminiert – die Programmiererin, das Unternehmen oder die Nutzerin?
- Welche Schutzmaßnahmen fordern die EU-KI-Verordnung (AI Act) und die UNESCO-Empfehlung zu KI-Ethik?

---

### 4.5 Reflexionsfragen für Lehrende

> Diese Fragen sind für die abschließende Gruppenreflexion (ca. 20 Minuten) konzipiert:

1. **Rollenverschiebung:** Wie hat sich Ihr Bild von der Lehrerrolle im Verlauf dieser Fortbildung verändert? An welcher Stelle haben Sie sich als Coach erlebt – und wie hat sich das angefühlt?

2. **Fachlicher Anker:** Welche **eine konkrete Unterrichtseinheit** in Ihrem Fach könnten Sie noch vor Ende des Schuljahres mit dem mBot auf Transformationsniveau umgestalten? Was brauchen Sie dafür noch?

3. **Institutionelle Hürden:** Welche schulischen Rahmenbedingungen (Lehrplan, Ausstattung, Kollegium, Zeit) stehen einem regelmäßigen mBot-Einsatz entgegen – und welche Strategien könnten helfen, diese zu überwinden?

4. **Ethische Verantwortung:** Als Lehrende vermitteln Sie durch den mBot implizit ein Bild davon, wie Algorithmen funktionieren. Welche Botschaft möchten Sie Ihren Lernenden hinterlassen?

---

### ✔️ Wissenscheck Modul 4

**Frage 10:** Eine Lehrerin lässt ihre Klasse in Gruppen einen mBot-Algorithmus entwickeln, der ein reales Logistikproblem simuliert. Anschließend präsentieren die Gruppen gegenseitig ihre Lösungen und geben Feedback. Auf welcher ICT-CFT-Ebene befindet sich diese Unterrichtseinheit?

[( )] Erwerbsebene – Anwendung
[( )] Vertiefungsebene – Infusion
[(x)] Gestaltungsebene – Transformation
[( )] Die Ebene ist ohne Lehrplan-Zuordnung nicht bestimmbar

---

**Frage 11:** Was versteht man im Kontext des mBot-Einsatzes unter „Bias-Audit"?

[( )] Eine Prüfung der Akkulaufzeit unter verschiedenen Bedingungen
[(x)] Eine systematische Überprüfung, ob das System unter bestimmten Bedingungen (z. B. Licht, Farbe) diskriminierende oder fehlerhafte Ergebnisse produziert
[( )] Eine Qualitätsprüfung des Zusammenbaus durch den Hersteller
[( )] Ein Softwaretest zur Überprüfung der Bluetooth-Verbindung

---

**Frage 12:** Welche der folgenden Bewertungsformen ist für kompetenzorientierte mBot-Projekte besonders geeignet?

[( )] Schriftlicher Multiple-Choice-Test über mBlock-Befehle
[( )] Bewertung der Fahrtzeit im Linienfolger-Wettbewerb
[(x)] Portfolio mit Dokumentation des Entwicklungsprozesses, Reflexionsnotizen und Peer-Feedback
[( )] Klassenarbeit über die Geschichte der Robotik

---

## 📋 Gesamtreflexion & Abschluss

### Mein Fortbildungsportfolio – Persönlicher Lernplan

> Füllen Sie diese Vorlage am Ende der Fortbildung aus. Sie bildet die Grundlage für das Transfer-Coaching in den nächsten 4 Wochen.

**① Rückblick: Was nehme ich mit?**

> *(Freitext-Notiz für Teilnehmende)*

Notieren Sie **drei Erkenntnisse** aus dieser Fortbildung, die Sie überrascht oder besonders bewegt haben:

1. ___
2. ___
3. ___

---

**② Meine Transfer-Einheit**

> *(Konkrete Planung)*

| | |
|---|---|
| **Fach & Jahrgangsstufe** | ___ |
| **Thema der Einheit** | ___ |
| **mBot-Szenario** | ___ |
| **ICT-CFT-Ebene** | Anwendung / Vertiefung / **Gestaltung** |
| **Kollaborative Rollen** | Navigator:in / Programmierer:in / Tester:in / Dokumentar:in |
| **Transferfrage zum Abschluss** | ___ |
| **Geplanter Zeitraum** | ___ |

---

**③ Meine nächsten Schritte**

Setzen Sie Prioritäten:

- [ ] Ich stelle einen mBot-Antrag / hole Informationen zur Anschaffung ein
- [ ] Ich zeige einer Kollegin / einem Kollegen die mBlock-Software
- [ ] Ich entwickle meine Transfer-Einheit schriftlich aus
- [ ] Ich führe die Transfer-Einheit durch und dokumentiere sie
- [ ] Ich teile meine Erfahrungen im Kollegium (Kurzvortrag, Schulentwicklungstag)
- [ ] Ich forsche nach Möglichkeiten zur Weiterqualifizierung (Gestalten-Ebene, KI-Ethik)

---

### Kursevaluation

> Ihre Rückmeldung verbessert diese Fortbildung für künftige Kohorten. Bitte nehmen Sie sich 5 Minuten:

**Wie bewerten Sie den Gesamtnutzen dieser Fortbildung für Ihre Unterrichtspraxis?**

[(1)] ⭐ Kein Nutzen erkennbar
[(2)] ⭐⭐ Geringer Nutzen
[(3)] ⭐⭐⭐ Mäßiger Nutzen
[(4)] ⭐⭐⭐⭐ Hoher Nutzen
[(5)] ⭐⭐⭐⭐⭐ Sehr hoher Nutzen

---

**Welches Modul hat Ihnen am meisten gebracht?**

[(1)] Modul 1 – Einstieg & ICT-CFT-Rahmen
[(2)] Modul 2 – Zusammenbau & erste Schritte
[(3)] Modul 3 – Programmieren mit mBlock
[(4)] Modul 4 – Transfer in den Fachunterricht

---

**Was sollte in einer Folgeveranstaltung vertieft werden?**

[[Python/Arduino-Programmierung (Textkodierung)]]
[[KI-Ethik und Algorithmus-Kritik im Unterricht]]
[[Fächerspezifische Unterrichtsbeispiele (z.B. Mathematik, Sprache, Ethik)]]
[[Bewertung und Portfolioarbeit mit mBot-Projekten]]
[[Inklusion und Differenzierung mit dem mBot]]

---

## 📚 Weiterführende Ressourcen

### Offizielle Rahmendokumente

- **UNESCO ICT-CFT Version 3 (2018):** [https://unesdoc.unesco.org/ark:/48223/pf0000265721](https://unesdoc.unesco.org/ark:/48223/pf0000265721)
- **UNESCO-Empfehlung zur Ethik der KI (2021):** [https://www.unesco.org/en/artificial-intelligence/recommendation-ethics](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics)
- **EU AI Act – Verordnung zur Künstlichen Intelligenz:** [https://digital-strategy.ec.europa.eu/de/policies/european-approach-artificial-intelligence](https://digital-strategy.ec.europa.eu/de/policies/european-approach-artificial-intelligence)

### mBot & mBlock

- **mBlock (Programmierumgebung, kostenlos):** [https://mblock.makeblock.com](https://mblock.makeblock.com)
- **Makeblock Education (Lehrmaterialien):** [https://education.makeblock.com](https://education.makeblock.com)
- **mBot-Dokumentation & Tutorial-Videos:** [https://www.makeblock.com/mbot](https://www.makeblock.com/mbot)

### Didaktische Ressourcen

- **AI4K12 Initiative – Fünf große Ideen der KI:** [https://ai4k12.org](https://ai4k12.org)
- **Google Teachable Machine (einsteigerfreundlich):** [https://teachablemachine.withgoogle.com](https://teachablemachine.withgoogle.com)
- **Informatik ohne Computer (CS Unplugged):** [https://www.csunplugged.org](https://www.csunplugged.org)
- **LiaScript – Freie Kursplattform:** [https://liascript.github.io](https://liascript.github.io)

### Weiterführende Literatur

- Bünning, F. & Tegelbeckers, H. (2024). *Artificial Intelligence in Technical and Vocational Education and Training: A Practical Guide for TVET Institutions.* UNESCO UNEVOC.
- UNESCO (2018). *ICT Competency Framework for Teachers, Version 3.* Paris: UNESCO.
- Selwyn, N. (2019). *Should Robots Replace Teachers? AI and the Future of Education.* Cambridge: Polity Press.

---

<div class="success-box">

🎓 **Herzlichen Glückwunsch!**

Sie haben alle vier Module des Fortbildungsprogramms *Kompetenzorientierter Unterricht mit dem mBot* abgeschlossen.

Das Ziel dieser Fortbildung war nicht, Sie zu Robotik-Expertinnen und -Experten zu machen. Es war, Ihnen einen **neuen pädagogischen Blick** zu ermöglichen – auf Technologie als Ermöglichungsstruktur, auf Lernende als Gestalterinnen und Gestalter, und auf sich selbst als Coach in einer sich wandelnden Bildungslandschaft.

*Der mBot ist ein Anfang. Was Sie daraus machen, liegt bei Ihnen.*

</div>

---

*Dieses Modul wurde entwickelt am ITVET – Lehrstuhl für Ingenieurpädagogik und Technische Berufsbildung, Otto-von-Guericke-Universität Magdeburg, UNESCO UNEVOC Centre Magdeburg.*

*Lizenz: Creative Commons CC BY 4.0 – Freie Nutzung für nicht-kommerzielle Bildungszwecke unter Nennung der Quelle.*

*LiaScript-Format: [https://liascript.github.io](https://liascript.github.io)*