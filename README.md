# Hybride trainingsplan 30 nov 2026 t/m halve marathon 18 april 2027

Kracht, HYROX en hardlopen in 20 weken, met kcal/macro's per dag, krachtregistratie onder elke krachtdag, gewicht- en omtrektracker.

## Publiceren met GitHub Pages
1. Maak op github.com een nieuwe repository (bijv. `hybride-plan`).
2. Upload `index.html` en `README.md` (Add file > Upload files > Commit).
3. Ga naar Settings > Pages, kies Branch `main` en map `/ (root)`, klik Save.
4. Na ±1 minuut staat het plan op `https://<jouw-gebruikersnaam>.github.io/hybride-plan/`.

## Data bewaren
Invoer (gewichten, vinkjes, metingen) staat in je browser (localStorage), niet automatisch in GitHub.
- Klik onderaan "Zo werkt het plan" op **Download data (JSON)** en commit `trainingsdata.json` in de repo (bijv. wekelijks).
- Op een ander toestel: **Importeer** het JSON-bestand.

## Het plan aanpassen
Wijzig `index.html` (bijv. oefeningen in `SES`, tempo's in `E_`, `T_`, `I_`, `H_`) en commit; de pagina werkt zichzelf bij.

## Als app op je telefoon (offline)
Upload ook `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-180.png`, `icon-192.png` en `icon-512.png` naar de repo (naast `index.html`).
- iPhone: open de Pages-link in Safari, deel-knop > Zet op beginscherm.
- Android: Chrome-menu > Toevoegen aan startscherm of Installeer app.
De app werkt daarna ook zonder internet; updates komen binnen zodra je online bent.

## Agenda
Onder "Uitleg" staat een knop **Agenda (.ics)**: download het bestand en open het op je telefoon om alle trainingen in je agenda te zetten.
