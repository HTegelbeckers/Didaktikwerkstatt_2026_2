<!--
author:   Mohr
version:  1.0.0
language: de
narrator: Deutsch Female
mode:     Presentation
comment:  Erkenntnisse von der Bildungsmesse Bildung.Digital 2026

@style
:root { --navy: #0d2137; --teal: #009b8d; --lteal: #b2dfdb; }

.dark { background: var(--navy); color: #fff; padding: 2em 2.5em; border-radius: 6px; }
.dark h1, .dark h2 { color: #fff; margin: 0 0 0.3em; }
.dark .accent { color: var(--teal); font-size: 1.4em; font-weight: bold; }
.dark .sub { color: #ccc; margin-top: 1em; font-size: 0.9em; }
.dark ul { color: #cfd8dc; }

.teal-head { background: var(--teal); color: #fff; padding: 0.4em 1em; border-radius: 4px 4px 0 0; font-weight: bold; margin-bottom: 0.5em; }
.card { border: 1px solid #ccc; border-radius: 6px; padding: 1em; background: #f9f9f9; }
.grid2 { display: grid; grid-template-columns: 1fr 1fr; gap: 1em; }
.grid3 { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 1em; }
.steps { display: flex; justify-content: space-between; gap: 0.5em; }
.step { text-align: center; flex: 1; }
.step .num { background: var(--teal); color: #fff; border-radius: 50%; width: 2em; height: 2em; display: flex; align-items: center; justify-content: center; margin: 0 auto 0.5em; font-weight: bold; }
.step .arr { color: var(--teal); font-size: 1.5em; align-self: center; }
.pros { background: #1b5e20; color: #fff; padding: 0.3em 0.8em; border-radius: 4px; margin-bottom: 0.5em; }
.cons { background: #b71c1c; color: #fff; padding: 0.3em 0.8em; border-radius: 4px; margin-bottom: 0.5em; }
.fact { background: var(--navy); color: #fff; padding: 0.7em 1em; border-radius: 4px; margin: 0.4em 0; }

.section-break { background: var(--teal); color: #fff; padding: 3em 2em; border-radius: 6px; text-align: center; }
.section-break h2 { color: #fff; font-size: 2em; }
@end
-->

# Digitale Bildung neu gedacht

<div class="dark">
<h1>Digitale Bildung<br><span class="accent">neu gedacht</span></h1>
<p>Prüfungssysteme mit Puavo &amp; KI-Unterstützung mit SchulKI</p>
<p class="sub">Erkenntnisse von der Bildungsmesse Bildung.Digital 2026</p>
</div>

---

## Vortrag von Puavo

<div class="section-break">
<h2>Vortrag von Puavo</h2>
<p>zu digitalen Prüfungen</p>
</div>

---

## Puavo – Warum digitale Prüfungen neu denken?

<div class="grid2">
<div>
<div class="teal-head">Hintergrund</div>
<div class="card">

**Puavo GmbH**
Know-how aus Finnland, aktiv auch in Deutschland (u.a. Harz / Thale)

**Ausgangslage**

- Stabiles digitales Prüfen an vielen Schulen noch schwer umsetzbar
- Schule muss weiterhin Endgeräte stellen
- Lehrende und Prüflinge vor Ort (in der Schule)

</div>
</div>
<div>
<div class="teal-head" style="background:#b71c1c">Typische Probleme</div>
<div class="card">

- Netzwerkprobleme während der Prüfung
- Schwierigkeiten bei Vorbereitung
- instabile Serverstrukturen
- technische Störungen im Prüfungsablauf

</div>
</div>
</div>

> **Bewährtes System aus Finnland – jetzt auch für deutsche Schulen**

---

## Next-Exam – Die technische Lösung

*Open-Source-Software aus Österreich, integriert in Puavo*

<div class="grid3">
<div class="card">

**Serverunabhängig**

Prüfungen ohne zentralen Server möglich – der Lehrer-Rechner übernimmt die Steuerung.

</div>
<div class="card">

**Zentrale Kontrolle**

Lehrkraft sammelt alle Antworten ein, überwacht alle Schülerrechner in Echtzeit.

</div>
<div class="card">

**Sicherer Modus**

Rechner stark eingeschränkt im Prüfungsmodus – unerlaubte Hilfsmittel werden verhindert.

</div>
</div>

---

*Pin-Code-Verbindung · PDF-Aufgaben · GeoGebra-Integration · Backup-Funktion · Mehrere Prüfungen parallel*

---

## Ablauf einer digitalen Prüfung mit Next-Exam

<div class="steps">
<div class="step">
<div class="num">1</div>
<strong>Vorbereitung</strong><br>
<small>Lehrkraft startet Next-Exam im Lehrer-Modus und legt Aufgaben fest</small>
</div>
<div class="step">
<div class="num">2</div>
<strong>Verbindung</strong><br>
<small>Schüler/innen starten im Prüfungsmodus, Verbindung via Pin-Code</small>
</div>
<div class="step">
<div class="num">3</div>
<strong>Durchführung</strong><br>
<small>Lehrkraft überwacht alle Schülerrechner live; Backups sichern gegen Datenverlust</small>
</div>
<div class="step">
<div class="num">4</div>
<strong>Abgabe</strong><br>
<small>Schüler/innen geben ab</small>
</div>
<div class="step">
<div class="num">5</div>
<strong>Bewertung</strong><br>
<small>Lehrkraft bewertet eingegangene Prüfungen</small>
</div>
</div>

---

## Next-Exam – Weitere Funktionen

<div class="grid3">
<div class="card">📄 <strong>PDF-Aufgaben</strong><br><small>Aufgabenstellungen können als PDF bereitgestellt werden</small></div>
<div class="card">📐 <strong>GeoGebra</strong><br><small>Mathematikprüfungen durch GeoGebra-Integration möglich</small></div>
<div class="card">🔤 <strong>Rechtschreibprüfung</strong><br><small>Gezielte Steuerung/Abschaltung der Rechtschreibkorrektur (inkl. Groß/Klein)</small></div>
<div class="card">💾 <strong>Backup</strong><br><small>Lehrkräfte und Schüler/innen können Backups erstellen</small></div>
<div class="card">🖥️ <strong>Parallele Prüfungen</strong><br><small>Mehrere Prüfungen gleichzeitig bei mehreren steuerbaren Rechnern</small></div>
<div class="card">🔒 <strong>Prüfungsmodus</strong><br><small>Rechner stark eingeschränkt – verhindert unerlaubte Hilfsmittel</small></div>
</div>

---

## SchulKI

<div class="dark">
<h2>SchulKI</h2>
<p class="accent">KI-gestützte Lehr-Lernumgebung für Schulen</p>
<p class="sub">von Schulverwalter GmbH · gegründet 2019 in Leipzig · von Lehrern und Informatikern</p>
<ul>
<li>SchulKI</li>
<li>beste.schule</li>
<li>homepage.schule</li>
<li>plan.schule</li>
</ul>
</div>

---

## SchulKI – Funktionen im Überblick

<div class="grid3">
<div class="card">🔐 <strong>Datenschutzkonformes ChatGPT</strong><br><small>Speziell für den schulischen Kontext entwickelt</small></div>
<div class="card">🖼️ <strong>Bildgenerierung</strong><br><small>Erstellung von Bildern und Aufgaben für den Unterricht</small></div>
<div class="card">🧑‍🏫 <strong>Chat-KI mit Persönlichkeiten</strong><br><small>Schüler/innen chatten mit historischen oder fiktiven Persönlichkeiten</small></div>
<div class="card">📚 <strong>Unterrichtsplanung</strong><br><small>Komplette Unterrichtssequenzen mit vorgegebenen Prompts (Lückentext)</small></div>
<div class="card">✏️ <strong>Korrekturunterstützung</strong><br><small>KI hilft Lehrkräften beim Korrigieren von Aufgaben</small></div>
<div class="card">🧩 <strong>Pädagogische Unterstützung</strong><br><small>Konkrete Hilfe in Problemsituationen für Lehrkräfte</small></div>
</div>

---

## SchulKI – Vor- und Nachteile

<div class="grid2">
<div>
<div class="pros">✔ Vorteile</div>

- Datenschutzkonform, speziell für Schulen
- Große Zeitersparnis für Lehrkräfte
- Vielfältige Einsatzmöglichkeiten (Texte, Bilder, Planung)
- Fördert Medienkompetenz und KI-Verständnis
- Unterstützung im pädagogischen Alltag

</div>
<div>
<div class="cons">✘ Nachteile</div>

- Fächer nur für allgemeinbildenden Bereich
- Mögliche Abhängigkeit von KI-Systemen
- Qualität abhängig von Prompt-Qualität
- Einarbeitung erforderlich
- Gefahr übermäßiger Abhängigkeit bei Schüler/innen

</div>
</div>

---

## Fazit & Ausblick

<div class="dark">

<div class="fact">✅ Puavo + Next-Exam bietet eine stabile, serverunabhängige Lösung für digitale Prüfungen</div>
<div class="fact">✅ SchulKI ermöglicht datenschutzkonformen KI-Einsatz direkt im Schulkontext</div>
<div class="fact">⚠️ Beide Systeme erfordern Einarbeitung und technische Grundvoraussetzungen</div>
<div class="fact">💡 Ergänzung durch Materialien (z. B. Klett) zur Reflexion von KI-Chancen und -Risiken empfohlen</div>

<p class="sub" style="margin-top:1.5em; text-align:center"><em>Digitale Bildung – sicher, praxisnah und zukunftsfähig</em></p>

</div>