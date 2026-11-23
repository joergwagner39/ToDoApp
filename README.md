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

## Daten
Alle Daten bleiben lokal im Browser (localStorage). Über das Menü **⋯** lässt sich ein
JSON-Backup exportieren bzw. importieren – z. B. um die Daten auf ein anderes Gerät zu übertragen.
