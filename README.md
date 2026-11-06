# Bruno Vianello — Portfolio

Il mio portfolio personale, dedicato al percorso dal digital marketing allo sviluppo web e blockchain.

Raccoglie la mia presentazione professionale, le competenze e una selezione di progetti: Qi Watch, copywriting e sperimentazione nell’ecosistema Ethereum.

**[Visita il portfolio](https://digitalbrunovianello.github.io/)**

## Il progetto

Ho scelto uno stile dark con accenti azzurri e richiami visivi a Ethereum, per rappresentare il mio interesse per il Web3. Nella Home ho inserito un ritratto personale composto da cifre binarie, rielaborato con supporto AI e integrato nello sfondo tramite CSS.

Il sito è disponibile in italiano e inglese e comprende tre pagine:

- **Home:** presentazione, aree di attività e progetti.
- **CV:** esperienze, competenze e formazione in formato HTML.
- **Contatti:** form e collegamenti professionali.

## Tecnologie

- HTML semantico.
- CSS con Sass.
- Griglia Bootstrap.
- Flexbox e CSS Grid.
- Media query per adattare il layout ai diversi schermi.

Il menu mobile utilizza una checkbox e il selettore CSS `:checked`, senza JavaScript. Il font Space Grotesk è ospitato localmente.

## Struttura dei file

- `index.html`, `cv.html`, `contatti.html`: pagine italiane.
- `en/`: pagine inglesi.
- `assets/scss/`: sorgente Sass.
- `assets/css/`: CSS compilato.
- `assets/img/`: immagini, favicon e copertina social.
- `assets/fonts/`: font e relativa licenza.
- `assets/docs/`: CV e report Ethereum.
- `assets/vendor/`: griglia Bootstrap e relativa licenza.

## Compilazione Sass

Il sorgente degli stili si trova in `assets/scss/style.scss`.
È necessario avere Node.js e npm installati.
Per installare Sass e generare il CSS, eseguire dalla cartella principale del progetto:

```bash
npm install
npm run build:css
```

Il sito contiene già il CSS compilato: non occorre eseguire questi comandi per visitarlo.

## Form di contatto

Il form utilizza la validazione HTML e l’azione `mailto:`. Richiede un’app di posta configurata e non effettua invio diretto dal sito.

## Pubblicazione

Il sito è pubblicato con GitHub Pages dal ramo `main`, utilizzando la cartella principale del repository.
