# Mockup Generator — Sponsor Leghe Fantacalcio

App statica per generare i mockup: scegli un template, carichi l'immagine sponsor
(dimensioni esatte del PSD) e scarichi il mockup finito. Tutto lato browser.

## Pubblicare su GitHub Pages
1. Crea un repository (es. `mockup-generator`) e carica tutti questi file
   mantenendo le cartelle (`index.html`, `templates.json`, `templates/`).
2. Repo → Settings → Pages → Source: `Deploy from a branch` → branch `main`, cartella `/root`.
3. Attendi il deploy: l'URL sarà `https://<utente>.github.io/mockup-generator/`.

## Aggiungere/aggiornare template
- Aggiungi il PNG bucato in `templates/green/` (e, se doppio layer, lo sfondo in `templates/layer0/`).
- Aggiungi la voce in `templates.json` con `name`, `w`, `h`, `hole` [x,y,w,h], `layer0` (true/false).

Nota: apri sempre via Pages o un server locale (non da `file://`, altrimenti `templates.json` non si carica).
