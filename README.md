# Registro di Disciplina - PWA

Questa è la versione Progressive Web App del Registro di Disciplina.

## File inclusi

- **index.html** — L'app completa
- **manifest.json** — Metadati dell'app (nome, icona, colori)
- **sw.js** — Service worker (funziona offline)

## Come deployare su Netlify

1. Vai su [netlify.com](https://netlify.com)
2. Fai login con GitHub (o email)
3. Clicca "Add new site" → "Deploy manually"
4. Trascina questa cartella (drag & drop)
5. Netlify fa il deploy automaticamente

Il tuo sito sarà raggiungibile a un link come: `https://mio-registro.netlify.app`

## Come installare l'app

Sul link del tuo sito:
- **Su telefono**: tocca il menu → "Aggiungi alla schermata home"
- **Su PC (Chrome/Edge)**: tocca l'icona di installazione in alto a destra

L'app si comporta come un'app vera: funziona offline, ha la sua icona, niente barra del browser.

## Sviluppo locale

Se vuoi provare in locale prima di deployare:

```bash
# Con Python 3
python3 -m http.server 8000

# Poi apri http://localhost:8000
```

Apri le developer tools (F12) e guarda che il Service Worker sia registrato.
