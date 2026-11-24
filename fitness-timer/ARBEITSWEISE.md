# Fitness-Timer: Arbeitsweise

Private App nur für Kevins eigenes Training. Gehört nicht zum Teaching Cockpit: nicht auf der Startseite, keine Kachel, kein QR. Erreichbar nur über den direkten Link (`noindex`).

## Entscheide (23.11.2026)
- Ohne Bilder, nur Textbeschreibungen.
- Bereiche: Warm-up, Training, Cooldown (gleiche Logik).
- Pro Übung eigene Trainingszeit und Pause; Seitenwechsel (links/rechts) nur bei Übungen, wo es passt (Flag `c`).
- Start-Countdown standardmässig 5 s, wählbar (0 = sofort).
- Letzte 5 Sekunden: Rückwärtszählen und Piepen.
- Schalter unter «Mehr → Einstellungen»: Vorbereitung, Rundenpause, Sprachansage, Vibration, Cooldown automatisch, Wochenplan.
- Ausgewählte Übungen in der Liste sind blau.

## Regeln
- Hochdeutsch, Schweizer Rechtschreibung (ss). Handy und iPad tauglich.
- Zuerst erklären, dann fragen. Nie ungefragt einspielen. Vor Änderungen Backup.
- Bei Cache-Änderungen in `sw.js` die Version `V` erhöhen.

## Offen
- Auf Geräten testen (Samsung Galaxy S25+, Tab, iPad): Ton, Vibration, Sprachansage, Bildschirm bleibt an.

## Übungsliste
- Standard-Übungen stehen in `DEF` (index.html). Neue Standard-Übungen: `libv` in `init()` und `mig()` erhöhen (aktuell 3), dann werden fehlende Übungen bei bestehenden Geräten ergänzt (nichts wird gelöscht).
- Auswahl vom 23.11.2026 ist eingebaut (Beine, Oberkörper, Rumpf, Cardio, Warm-up, Cooldown).
- Zweiseitige Übungen (Flag `s`, immer links und rechts): alle Dehnungen, Ausfallschritte (alle Varianten), Step-ups, Bulgarian Split Squats, einbeinige Übungen, Seitstütz, Unterarmstütz mit Beinheben, Beinpendeln, Hüftöffner. Wechselnde Übungen (Skater, Mountain Climbers, Bicycle Crunches) zählen als eine Übung.
