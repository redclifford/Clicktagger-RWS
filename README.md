# Click Tagger Plus

**Versie:** v3.9  
**Omschrijving:** Een lichte webapp om clicks te loggen met o.a. GPS-ondersteuning en CSV-export. Geoptimaliseerd voor mobiel/tablet.

## Wat zit erin
- **Persistente data:** gegevens blijven bewaard via `localStorage` tot je handmatig reset.
- **Route-veld:** alleen cijfers en de tekens `-` en `/` toegestaan; **max 5** tekens.
- **Exportnaam:** elke `/` in de route wordt **`-`** in de bestandsnaam.
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
Nog niet ingesteld. Voeg eventueel zelf een **LICENSE** toe (bijv. MIT) als je dat wilt.
