# Note di Versione - QRZCB Mobile

## Versione 3.0.9 (Build 37) - Settembre 2026

### Novità e Miglioramenti
* **Mappa Unificata Identica alla Versione 3.0.2**: Architettura cartografica della mappa FT8 completamente allineata al motore collaudato delle pagine profilo della 3.0.2 (`LocatorMapWidget`). Risolti definitivamente i problemi di zoom e panning: aggiunti pulsanti a schermo `+` e `-`, reset centro Europa e trascinamento fluido.
* **Affidabilità Totale Tile & Zero Dipendenze API**: Tessere OpenStreetMap con fallback istantaneo su ArcGIS World Street Map ed elaborazione scura nativa: nessuna piastrella mancante o errore di caricamento.
* **Dashboard FT8 Live Aperta di Default**:
  - **Grafico Feed 30 Minuti**: Curve continue e morbide (Bézier cubiche) per **PSK-Reporter** e **XZGroup Net** con indicazione totale spot.
  - **Tabella Ultimi 10 Spot Real-Time**: Elenco compatto che scorre con badge di feed (`[XZ]` e `[PSK]`), `TX ➔ RX`, SNR, frequenza, locatore e tempo relativo (`Adesso`, `12s fa`, ecc.).
  - Indicatore dinamico verde `FT8 LIVE` per confermare la ricezione continua dei pacchetti.
* **Switch View**: Possibilità di commutare la visualizzazione tra **SPLIT** (Mappa + Feed), **MAPPA** a tutto schermo e **TABELLA** a tutto schermo.

---

## Versione 3.0.8 (Build 36) - Settembre 2026

### Novità e Miglioramenti
* **Terminatore Solare Sempre Attivo**: Calcolo astronomico della declinazione solare in tempo reale UTC.
* **Casetta Stazione Utente**: Visualizzazione della propria casetta sul locator solo su conferma esplicita dell'utente.
* **Pulizia TopBar**: Rimossa la label di notifica `UPDATE` per mantenere essenziali le indicazioni di stato.

---

## Versione 3.0.7 (Build 35) - Settembre 2026

### Novità e Miglioramenti
* **Mappa FT8 Interattiva**: Tasto FOCUS, tasto rotante orari, linee vettoriali di collegamento QSO e rate-limiting server.
* **Feed Verticale Social**: Formato verticale per le schede con sfocatura automatica delle bande laterali.
* **Profilo Esterno & My eQSLs**: Badge `nickname_cb` azzurrino integrato anche nei profili cercati.

---

## Versioni Precedenti

### Versione 3.0.6 (Build 34)
* Menu drawer riorganizzato con Profile e My eQSLs in primo piano.
* eQSL intere nel profilo senza tagli.
* Suggerimenti ricerca limitati a 5 risultati.

### Versione 3.0.5 (Build 33)
* Dati certi al 100% da database ufficiale.
* Filtro feed per foto profilo e stazione popolate.
