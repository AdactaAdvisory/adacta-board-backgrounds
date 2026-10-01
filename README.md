# adacta-board-backgrounds

Sfondi HTML standard per screen e maschere Board, da usare con il webviewer.
Nessun testo e nessun dato di cliente: solo la struttura di sfondo.

Pubblicati con GitHub Pages: `https://adactaadvisory.github.io/adacta-board-backgrounds/v1/<nome>.html`

| Sfondo | URL |
|---|---|
| Pianificazione v2 (barra blu + colonna selezioni, con ombre e rilievo) | `/v2/pianificazione.html` |
| Pianificazione v1 (versione piatta originale) | `/v1/pianificazione.html` |

Parametri opzionali da query string (colori con `%23` al posto di `#`): `bar`, `accent`, `line`, `side`, `head`, `gap`. Con `?demo=1` compaiono i testi segnaposto, solo per verificare la leggibilita'.
Esempio: `pianificazione.html?bar=%23003366&side=240`

Le modifiche a `v1/` cambiano tutte le maschere che lo usano: per cambiamenti incompatibili si crea `v2/`.

## Sperimentale

`/sperimentale/three-terreno.html` — terreno di punti e linee in three.js (da cdnjs), interattivo: segue il mouse, ogni click lancia un onda gialla, il solido wireframe e cliccabile. Parametri: `fx=0` (fermo), `dens=0.5..2`, `demo=1`. Non e uno sfondo stabile.

`/sperimentale/ponte.html` — pagina di prova del ponte Board -> webviewer: legge valori da frammento/query, li mostra con conteggio animato e registra come Board carica la pagina (ricarica o hashchange, lunghezza URL, iframe, postMessage). Solo valori finti.

## Componenti

`/componenti/home.html` — home del modello (testata, avanzamento del ciclo, tessere KPI con confronto e andamento, avvisi, scadenze). Dati dal frammento dell URL; senza parametri mostra dati di esempio. Il contratto dei parametri e nel commento in testa al file.
