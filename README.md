# Click Tagger Plus

Een eenvoudige, offline werkende click tagger tool.

- **Versie**: v3.7
- **Licentie**: MIT — © 2025 Bart Leemeijer
- **Ontwikkeld namens**: ABR Activatie
- **Datum**: 2025-10-16

## Snel starten (GitHub Pages)

1. Maak een nieuwe openbare GitHub repository, bijvoorbeeld `click-tagger-plus`.
2. Upload de bestanden uit deze map:
   - `index.html`
   - `.nojekyll`
   - `LICENSE`
   - `NOTICE` (optioneel, voor context)
   - `README.md` (dit bestand)
3. Commit & push naar de `main` branch.
4. Ga naar **Settings → Pages** en zet **Deploy from a branch** aan met:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Je site staat binnen enkele seconden/minuten live op `https://<jouw-gebruikersnaam>.github.io/<repo-naam>/`.

## Bestandsnaam bij export
Bestanden die je downloadt of deelt krijgen automatisch (indien ingevuld) de `Naam` en `route<nr>` toegevoegd.

Voorbeeld: `16-10-2025_Jan_route12.csv`

## Ontwikkelnotities
- CSV-kolommen: `Naam, Route, ObjectID, Latitude, Longitude, Timestamp, 5stuks`
- De waarde van **Route** is beperkt tot maximaal 3 cijfers.
- `index.html` is volledig self-contained en werkt zonder build-stap.

---

© 2025 Bart Leemeijer — MIT License. Ontwikkeld namens ABR Activatie.
