# Click Tagger Plus

_Ontwikkeld door **Bart Leemeijer** namens **ABR Activatie**._

**Versie:** v3.5  
**Datum:** 15-10-2025

Een lichte webapp om snelle *click tags* te registreren (x1/x5), optioneel GPS vast te leggen en direct naar CSV te **downloaden** of te **delen**.

## Highlights
- Bevat `.nojekyll` voor GitHub Pages (voorkomt Jekyll processing).
- Grote x1/x5-knoppen met extra ruimte eronder (48px) voor minder mis-taps.
- CSV export **Download** en **Delen** gebruiken **dezelfde bestandsnaam**.
- Bestandsnaam-formaat: `DD-MM-YYYY[_Naam].csv` (bijv. `15-10-2025_Piet.csv`).
- Donkere modus, eenvoudige UI, mobile-first.
- Werkt volledig client-side (geen backend).

## Snel starten
1. **Lokaal openen:** open `index.html` in je browser.
2. **GitHub Pages:**
   - Maak een nieuwe repo (bijv. `click-tagger-plus`).
   - Upload de bestanden of push via git.
   - Ga naar **Settings › Pages** en kies **Deploy from branch** op `main`, **/ (root)**.
   - Je app staat dan op `https://<jouw-account>.github.io/<repo-naam>/`.

## Bestandsnaam export
- Formaat: `DD-MM-YYYY[_Naam].csv`
- De `Naam` komt uit het Naam-veld in de app; leeg laten betekent geen `_Naam` suffix.

## Browser tips
- **Android/Chrome**: delen + downloaden werken prima.
- **iOS/Safari**: delen als bestand wordt ondersteund op recente iOS-versies, maar gedrag kan variëren.
- Sta locatie-toegang toe als je GPS wilt loggen.

## Changelog
- **v3.5**: bestandsnamen omgezet naar `DD-MM-YYYY[_Naam]` voor **zowel** Download als Delen.
- **v3.4**: `tags_` prefix verwijderd; extra knopruimte naar 48px.
- **v3.3**: extra ruimte onder x1/x5; gedeelde bestandsnaam geharmoniseerd.

## Licentie
Zie **LICENSE** (MIT). Pas eventueel de naam/rechthebbende aan in het copyright-blok.

---

_Vragen of wensen? Open een issue of stuur een bericht._
