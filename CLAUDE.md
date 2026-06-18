# dalaokonomi.no

Markedsføringsside for **Dala Økonomi AS** (regnskapskontor i Brumunddal, del av Saga KL).

## Stack
- Én selvinneholdt `index.html` med vanilla HTML/CSS/JS
- Ingen build-steg, ingen `package.json`
- Bilder/favicons i rot + `images/`

## Deploy
- Netlify-prosjekt: `dalaokonomino` → https://dalaokonomi.netlify.app (og dalaokonomi.no domenet)
- Auto-deploy fra `main` ved push til GitHub (`erlendsandberg/dalaokonomi.no`)
- Konfig: `netlify.toml`

## Arbeidsflyt
- Rediger `index.html` direkte
- Forhåndsvis ved å åpne fila i nettleser, eller `netlify dev`
- `git push` → live etter ~30 sek
