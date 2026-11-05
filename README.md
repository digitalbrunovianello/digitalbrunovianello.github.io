# Bruno Vianello — Portfolio

Portfolio statico in italiano e inglese, pronto per GitHub Pages.

## Struttura
- `index.html`, `cv.html`, `contatti.html`: pagine italiane.
- `en/`: versioni inglesi.
- `assets/scss/style.scss`: sorgente degli stili Sass.
- `assets/css/style.css`: CSS compilato, da pubblicare insieme al sito.
- `assets/vendor/bootstrap-grid.min.css`: griglia Bootstrap locale (vedi licenza allegata).
- `assets/fonts/`: Space Grotesk locale con licenza OFL.
- `assets/docs/`: report Ethereum e CV originale forniti dall’autore.

## Stili
Installare le dipendenze con `npm install`, poi eseguire `npm run build:css` dopo aver modificato Sass. `npm run watch:css` aggiorna il CSS durante il lavoro. Nessun comando è necessario per visitare il sito già compilato.

## Contatti
Il sito usa esclusivamente HTML e CSS, senza JavaScript. Il menu mobile è controllato da una checkbox e dal selettore CSS `:checked`, utilizzabile anche da tastiera. La validazione del modulo è nativa HTML (`required`, `type="email"`). L’azione `mailto:` richiede un’app di posta configurata: il recapito e la composizione dei dati dipendono dal browser e dal client. Il collegamento email diretto offre un’alternativa. Non è implementato invio server. Sass è soltanto uno strumento di compilazione in sviluppo: il sito pubblicato carica HTML e CSS.

## Prima della pubblicazione
- Verificare date, ruoli e livelli di competenza del CV con l’autore; il PDF conserva il curriculum originale fornito.
- Aggiungere una privacy policy coerente con i servizi effettivamente utilizzati: il link non è stato inventato.
- Impostare il dominio definitivo e aggiornare `og:image` con l’URL pubblico assoluto; aggiungere canonical, og:url e hreflang assoluti per ogni pagina.
- La copertina `assets/img/social-cover.png` è pronta; il comportamento social va verificato dopo la pubblicazione.
- GitHub Pages: pubblicazione dal ramo scelto, cartella radice. Le risorse sono relative e funzionano anche in un project site.
- Nessuna modifica ai DNS o al servizio email è stata effettuata.
- Le illustrazioni sono rappresentazioni grafiche editoriali, non fotografie o screenshot dei prodotti.
