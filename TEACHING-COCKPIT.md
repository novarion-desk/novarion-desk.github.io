# Teaching Cockpit: Arbeitsweise

Gemeinsame Notizen für alle Apps und die Startseite, für die Weiterarbeit mit KI-Assistenz.
Jede App hat zusätzlich eine eigene Datei (z. B. `ARBEITSWEISE.md` im Repo `grammatik-trainer`).

## Die Website

- Startseite: https://novarion-desk.github.io/ (dieses Repo, GitHub Pages).
- `index.html` ohne externe Abhängigkeiten. `img/` Vorschaubilder, `icons/` Symbole, `qr/` QR-Codes.
- Oben Fächerleiste und Filter Lehrpersonen/Schüler. Mittlere Kacheln mit Bild (2 Spalten Handy, 4 Computer).
- Sicherung der alten Startseite: Zweig `backup-startseite-2026-11-20`.
- Auf der Website nichts, was auf eine Person oder eine Schule zurückführt. Untertitel: «Apps für den Unterricht».

## Apps (Repos unter `novarion-desk`)

| Repo | App | Hinweis |
|---|---|---|
| `grammatik-trainer` | Grammatik Trainer | Auf der Website als Demo im Schüler-Modus («Beta») |
| `sek-planer` | Sek Planer | Wochenplanung, «Invite only», nicht für Schüler |
| `sek-zufall` | Zufallsgenerator | Login nur für Lehrpersonen, Demo-Klasse ohne Speichern |
| `notentrainer` | Notentrainer | Notenlesen Violin- und Bassschlüssel |
| `lightning` | Lightning | Live-Checks und Exit-Tickets, «Invite only · Demo frei» |
| `zeitstrahl` | Zeitstrahl | Geschichte/RZG, noch nicht auf der Website |
| `tensetrainer` | Tense Trainer | Englisch-Zeitformen |
| `englishlab` | EnglishLab | Englisch-Grammatik mit Theorie, Übungen (A/B/C), Suche, Wörterbuch, Lehrerbereich mit Folien; Kachel aktiv mit Öffnen, Demo und QR; Version 1.1 mit Vokabeltrainer |
| `caroule` | Ça roule | Französisch-Zeitformen, Kachel zunächst «Demnächst» ohne Link |
| `piano-levels` | Piano Levels | Platzhalter-Kachel (demnächst) |

## Gemeinsame Regeln

- Hochdeutsch, Schweizer Rechtschreibung (ss, kein ß). Apps zuerst auf Deutsch.
- Apps müssen auf dem iPad laufen (Schüler arbeiten mit iPads) und sich als App installieren lassen (eigenes Icon).
- Lehrer-Login mit Firebase (Auth/Firestore), Schüler ohne Login. Schlüssel nie in den Code schreiben.
- Zuerst analysieren und erklären, dann fragen. Nie ungefragt neu bauen oder einspielen.
- Vor jeder Änderung ein Backup. Inhalte: Prüfliste für die fachliche Kontrolle, erst nach ausdrücklichem Ja pushen.
- Design- und Funktionsänderungen immer auch in der Demo-Version und auf der Website mitführen.
- Neue Apps erst auf die Website, wenn es ausdrücklich gesagt wird. Bis dahin Kachel «Demnächst» ohne Link und QR.
- Später, noch nicht einbauen: Abo-Knopf pro App oder für die ganze Suite (Monatsabo).

## Offene Punkte

- Zeitstrahl: Entwurf im Zweig `entwurf-datum-ausfuehrlich` (Datum zur Jahreszahl, ausführlicher Text, PDF-Export, Teilen nur als Ansicht). Kachel noch offen (Fach «Fachübergreifend» oder «RZG/Geschichte»).
- Grammatik Trainer: Inhalte Thema für Thema nach den Unterrichtsunterlagen. Stand siehe `ARBEITSWEISE.md` im Repo `grammatik-trainer`.
