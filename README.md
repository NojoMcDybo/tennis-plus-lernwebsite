# Tennis Plus — Lernwebsite zur Prüfung SoSe 2026

Interaktive Prüfungsvorbereitung für **Tennis Plus (075348)**, Universität Münster, Institut für Sportwissenschaft — Binnenbruck / Brunert, Mi 10–12.
Zielprüfungen: **benotete fachpraktische Prüfungsleistung (30.07.26)** und **Klausur Rückschlag (31.07.26, 60 Min)**.

**Öffnen per Doppelklick auf `index.html`.** Keine Dependencies, kein Server, keine Installation. Läuft offline (Google Fonts werden bei Internetverbindung nachgeladen, sonst greift der System-Fallback).

---

## Struktur

Die Modulstruktur folgt **exakt dem Veranstaltungsplan** — nicht einem Buch-Inhaltsverzeichnis. Der Semesterverlaufsplan ist die Themenliste der Klausur.

| Modul | Semestertermin | Inhalt |
|---|---|---|
| **Start** | — | Hero mit Reveal-Effekt, Lernpfad, Studien- vs. Prüfungsleistung, die 10 Stufen der Schlagfolge, Vorgaben zur Stundengestaltung |
| **Spiele** | 22.04. · 29.04. · 24.06. | Übersichtstabelle aller 7 Rückschlagspiele (Feldmaß, Ball, Teamstärke, Zählweise) + Steckbriefe mit den Sonderregeln zum Aufdecken |
| **Regeln** | 22.04. | Interaktives Court-SVG (maßstabsgetreu, klickbare Linien/Zonen/Netz), Zählweise, 9 Calls & Verstöße mit Lernmodus |
| **Vermittlung** | 15.04. · 06.05. | **Die Vermittlungskonzepte-Tabelle (1:1)**, Original-Ballschulgrafiken, DTB-Kinderkonzept, Ballschule Tennis, Münsteraner Modell, LTAD, Taktik-Spiel-Modell, Spielintelligenz in 4 Phasen, Schulpraxis-Fragen |
| **Taktik** | 13.05. · 20.05. · 03.06. · 10.06. | Die 4 taktischen Handlungsziele als klickbare Treppe, 5 taktische Prinzipien, 5 Phasen der taktischen Handlung, Ampelprinzip, Winkelhalbierende, Winner/Forced/Unforced Error |
| **Technik** | 13.05. · 03.06. | Vorhand, Rückhand, Aufschlag, Volley — Strichzeichnungen, Bewegungsphasen, Knotenpunkte, Fehlerbilder, Vermittlungswege, methodische Reihe für die Schule |
| **Doppel** | 17.06. | 7 Doppel-Grundsituationen mit Originalfolien, die 4 Organisationsformen, Aufgaben des Netzspielers |
| **Turniere** | 08.07. | Spiel-/Wettkampf-/Turnierform, Turnierformate, Formen-Katalog (Kartotheken), Spielplan 08.07. |
| **Quiz** | — | 24 Zahlen-Drill-Flipkarten + **vollständige Wissensprüfung mit 100 MC-Fragen** über 8 Bereiche, Auswertung pro Bereich, Wiederholung nur der falschen Fragen, jede Antwort mit Belegstelle |

Navigation: Glass-Pill oben, Pfeiltasten ← / → wechseln das Modul, jedes Modul endet mit Zurück/Weiter.

---

## Bilder

### Fotos (Modul-Hintergründe)

Quelle: `OneDrive\Websites\Tennis` — die PNGs wurden nach `img/` als JPG (max. 2000 px, Qualität 86) konvertiert. Aktuelle Zuordnung:

| Datei in `img/` | Foto | Warum dort |
|---|---|---|
| `hero-leer.jpg` | Empty court | Hero-Basisbild |
| `hero-voll.jpg` | gameday evening | Hero-Reveal — identische Perspektive, deshalb funktioniert der Kometen-Schweif. Der aufgedeckte Bereich bleibt 3 s stehen, dann verblasst er |
| `start.jpg` | gameday evening | Match Day unter Abendlicht |
| `spiele.jpg` | Lockerroom | Material, Schläger, Bälle — die Gerätefamilie |
| `regeln.jpg` | Empty court | Linien und Netz klar sichtbar |
| `vermittlung.jpg` | Lockerroom empty | ruhig, strukturiert — Textmodul |
| `taktik.jpg` | Full stadium top view | Draufsicht = Geometrie, Winkelhalbierende |
| `technik.jpg` | Referee Chair | Netz-Nahsicht |
| `doppel.jpg` | Full stadium top view | Draufsicht = Positionen und Stellungsspiel |
| `turniere.jpg` | gameday evening | Wettkampf unter Abendlicht |
| `quiz.jpg` | Lockerroom empty | ruhig, kein Ablenkungsmaterial |

**Neue Bilder nachrüsten:** JPG in `img/` legen und exakt nach der Modul-ID benennen (`start`, `spiele`, `regeln`, `vermittlung`, `taktik`, `technik`, `doppel`, `turniere`, `quiz`). Die Seite lädt sie automatisch — kein Code-Eingriff. Fehlt ein Bild, greift der Gradient-Fallback, die Seite bleibt intakt.

**Hero-Regel:** `hero-leer.jpg` und `hero-voll.jpg` müssen identische Perspektive und Auflösung haben, sonst springt das Bild beim Reveal.

### Originalgrafiken aus den Seminarunterlagen (`img/gfx/`)

Aus den PDFs/DOCX extrahiert, freigestellt bzw. entzerrt:

- **Schläger** (`schlaeger-*.png`, freigestellt): Tennis, Padel, Pickleball, Touchtennis, Streetracket, Tamburello, Speckbrett — aus *Übersicht Rückschlagspiele*. Eingebaut in die Rückschlagspiel-Tabelle und die Steckbriefe.
- **Doppeltaktik-Originalfolien** (`doppel-*.jpg`): je eine Folie pro Spielsituation aus *Doppeltaktik.pdf* (Brunert/Feddermann, Trainingsplaner Tennis) — wird im Doppel-Modul synchron zur gewählten Situation angezeigt, Klick öffnet die Lightbox. Zusätzlich die Übersichtsfolie und die Drei-Situationen-Grafik aus der Stundenvorbereitung.
- **Ballschule** (`ballschule-*.jpg`): Stufenmodell (Stufe 1–5), Basiskompetenzen A/B/C, Ziele der Rückschlagspiele, Ziele der Ballschule Tennis (8×7×6) — aus *Input Heidelberger Ballschule* und *Ablauf 1. Veranstaltung*. Zwei davon lagen im PDF um 180° gedreht und wurden gerichtet.

Die **Vermittlungskonzepte-Tabelle** ist keine Grafik, sondern als echte HTML-Tabelle nachgebaut (5 Spalten: DTB-Kinderkonzept · Ballschule Tennis · Münsteraner Modell · LTAD · Taktik-Spiel-Modell) — dadurch durchsuchbar, kopierbar und auf dem Handy lesbar.

---

## Quellen

Alle Inhalte stammen aus den Seminarmaterialien im übergeordneten Tennis-Ordner. Jede Sektion trägt eine `Beleg:`-Zeile (33 Belegstellen insgesamt).

**Seminarunterlagen (Binnenbruck / Brunert, Uni Münster):**
- Veranstaltungsplan Tennis Plus, SoSe 2026 / 075348, V03
- Übersicht Rückschlagspiele, Fachpraktisches Seminar Tennis Plus
- Vermittlungskonzepte Teil 2 (© 2026 WBrunert)
- Input integrative Sportspielvermittlung · Input Heidelberger Ballschule
- Spiel- und Wettkampfformen — Zusammenstellung Brunert (Kartothekensammlung, tenniskartotheken.de)
- Weitere Spiel-, Turnier- und Wettkampfformen, 08.07.2026
- Ablauf Tennis 1. Veranstaltung SS 26 · Ablauf Tamburello/Streetracket, 24.06.2026
- Binnenbruck, A. (2017). *Wolf im Schafspelz: der Tamburello-Schläger*

**Team-Skripte / Protokolle:**
- 29.04.2026 — Pickleball, Touchtennis, Speckbrett
- 06.05.2026 — Zusammenfassung Vermittlungsmodelle
- 13.05.2026 — Ballwechsel in Gang halten (Technik VH/RH)
- 20.05.2026 — Gegnerische Punktgewinne vermeiden (Taktische Prinzipien)
- 03.06.2026 — Gegner unter Druck setzen (Aufschlag/Volley)
- 10.06.2026 — Eigene Punkte erzielen (Return, Forced Errors, Ampelprinzip)
- 17.06.2026 — Taktiken im Doppel (Organisationsformen, Taktikmodell Doppel)

**Fachliteratur:**
- Born, P., Grambow, R. & Meffert, D. (2025). *Tennis — das Praxisbuch für Studium, Training und Freizeitsport*. Springer Spektrum.
- Roth, C., Ebert, M. & Roth, K. (2022). *Ballschule Tennis. Das ABC für Tenniskinder*. Hofmann.
- Deutscher Tennis Bund (2001). *Tennis-Lehrplan Band 1: Technik & Taktik*. BLV.
- Bühler, J. et al. (2012). *Player Development — Grundlagen Taktik und Technik*. Swiss Tennis.
- Schönborn, R. (2016). *Tennis Techniktraining*. Meyer & Meyer.
- Bezzenberger, R. & Brunert, W. (2020). *Tennis Turnierformen — Erlebnis statt Ergebnis*. Bezzenberger.
- Brunert, W. & Feddermann, F. *Trainingsplaner Tennis* (CD) — Doppeltaktik.

**Regelwerk:**
- ITF Rules of Tennis, Rule 1 (Court), Rules 5–7 (Score), Rules 9/16/18/19/22/24
- USA Pickleball Rules, Section 2 (Court & Equipment)
- FIP Padel Regulations (Court Dimensions)

> **Regel:** Weicht die Seminar-Version vom internationalen Standard ab (z. B. Pickleball 13,4 × 6 m statt 13,41 × 6,10 m), wird die **Seminar-Version prominent gelehrt** und die Abweichung in einer Warn-Box erklärt. In der Klausur zählt die Seminar-Version.

---

## Repository

- `index.html` — die komplette Seite, Single-File, keine Dependencies
- `img/` — Modul-Hintergründe und Technik-Strichzeichnungen (komprimiert, produktionsfertig)
- `img/gfx/` — Originalgrafiken aus den Seminarunterlagen
- `fotos/` — die Original-PNGs als Quellmaterial (unkomprimiert)
- `README.md`

Privates Repo: `github.com/NojoMcDybo/tennis-plus-lernwebsite`. GitHub Pages ist bei privaten Repos nur mit Pro-Account möglich — die Seite läuft ohnehin per Doppelklick auf `index.html`.

---

## Qualitätssicherung

- jsdom-Smoke-Test: keine Runtime-Errors, alle 9 Module schaltbar, alle Renderer liefern (18 Court-Hitboxen, 9 Call-Karten, 24 Flipkarten, 7 Doppel-Situationen, 4 Treppenstufen), Wissensprüfung mit allen 100 Fragen komplett durchspielbar inkl. Auswertung pro Bereich.
- Alle Platzmaße gegen die ITF Rules of Tennis geprüft, alle Seminarzahlen gegen die Originaldokumente.
