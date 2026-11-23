# ToDoApp

Einfache ToDo-App mit zwei getrennten Bereichen: **Beruflich** und **Privat**.

## Starten
`index.html` im Browser öffnen – fertig. Keine Installation, kein Server nötig.

## Funktionen
- **Beruflich:** Kachel für jeden betreuten Spieler. Ein Klick öffnet die Spielerseite mit
  - Übersicht zu Versicherungen, Wohnung, Adresse & Kontakt, Steuer, Auto, Familie (Felder + Notizen)
  - eigenen Aufgaben, jeweils einem Bereich zugeordnet, mit Fälligkeitsdatum und „Wichtig“-Markierung
  - Kennzahlen (offen / fällig in 7 Tagen / überfällig) und Liste „Als Nächstes fällig“ über alle Spieler
- **Privat:** eigene Aufgabenliste, gruppiert nach Haushalt, Finanzen, Gesundheit, Familie, Termine, Einkaufen, Sonstiges.
- Aufgabe per Doppelklick bearbeiten, Spieler hinzufügen / umbenennen / entfernen.

## Daten & Synchronisation
- **Als Claude-Artifact geöffnet** (claude.ai, im Browser oder in der Claude-App): Die Daten liegen privat in deinem
  Claude-Konto und sind auf Handy und Laptop automatisch gleich. Oben links zeigt ein Punkt den Status
  (grün = synchronisiert). Nur du selbst siehst diese Daten, auch wenn du den Link teilst.
- **`index.html` lokal geöffnet:** Die Daten bleiben nur in diesem Browser (localStorage).
- Über das Menü **⋯** lässt sich jederzeit ein JSON-Backup speichern bzw. einspielen.

Für das Artifact werden die ersten 7 und die letzten 2 Zeilen von `index.html` (Dokument-Rahmen) weggelassen:
`sed '1,7d' index.html | head -n -2 > artifact.html`
