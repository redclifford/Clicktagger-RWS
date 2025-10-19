# Click Tagger Plus

**Versie:** v3.10  
**Omschrijving:** Lichte webapp om clicks te loggen met o.a. GPS-ondersteuning en CSV-export. Geoptimaliseerd voor mobiel/tablet.

## Wat zit erin
- **Persistente data:** gegevens blijven bewaard via `localStorage` tot je handmatig reset.
- **Route-veld (v3.10):** **alleen cijfers**, **max 5** tekens (UI + JS).
- **Exportnaam:** gebruikt alleen de cijfers uit de route.
- **Kleine knoppen:** Start/Stop GPS, Delen/Download CSV, Undo, Dark mode.
- **Sneltoetsen:** spatie (x1), `5` (x5), `e` (export), `g` (GPS aan/uit).
- **Wake Lock**-optie (indien ondersteund door het apparaat).

## Publiceren op GitHub Pages
1. Maak een nieuwe GitHub-repository (bijv. `click-tagger-plus`).
2. Upload de bestanden uit deze map (minimaal **index.html** en **.nojekyll**).
3. Commit naar de `main` branch.
4. Ga naar **Settings → Pages** en kies: **Source: Deploy from a branch**, **Branch: main**, **Folder: /** (root). Sla op.
5. Je site komt online op: `https://<jouw-gebruikersnaam>.github.io/<repo-naam>/`

> Het bestand **.nojekyll** zorgt ervoor dat GitHub Pages niets door Jekyll laat verwerken en de site als pure static files bedient.

## Lokale ontwikkeling
Open gewoon **index.html** in je browser. Je hebt geen build-stap of tooling nodig.

## Licentie
MIT — zie het bestand **LICENSE**. Vergeet niet `<Your Name>` in `LICENSE` te vervangen door je eigen naam.
