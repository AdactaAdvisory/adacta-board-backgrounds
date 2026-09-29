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
