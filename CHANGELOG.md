# Note di Versione - QRZCB Mobile

## Versione 3.1.2 (Build 41) - Settembre 2026

### Novità e Miglioramenti
* **Mappe Diurne Uniformi in Tutta l'Applicazione**: Rimossa completamente la mappa notturna e qualsiasi filtro colore scuro da tutte le sezioni dell'app, inclusa la schermata FT8 27MHz Map, il profilo personale e i profili degli altri operatori (`LocatorMapWidget`). Resa geografica naturale e nitida.
* **Nuovi Pin FT8 Distinti per Rete**:
  - **PSK-Reporter**: Pallino nero pieno.
  - **XZGroup Net**: Quadratino nero pieno.
  - **Utenti Registrati QRZCB.io**: Badge ciano `#29D9D5` con lettera **W** nera marcata al centro (tondo per PSK, quadrato per XZGroup).
* **Interazione Pin & Isolamento QSO**: I nominativi sono nascosti di default per massima pulizia cartografica; toccando un pin appare il nominativo sotto di esso e viene isolato solo il traffico di quella stazione.
* **Linee QSO Verde Lime Sottili**: Linee di collegamento tra stazioni ridotte di spessore e renderizzate in Verde Lime (`#32CD32`) ad alta visibilità.
* **Tasto FOCUS Dinamico (Rosso Acceso / Spento)**: Posizionato al centro in basso sull'area mappa. Rosso spento quando inattivo, rosso acceso brillante con alone quando attivo. Toccando un pin si attiva il focus; toccando il tasto si disattiva tornando a tutti gli spot. Se l'utente non ha spot recenti, compare la notifica **`NO REPORT`** per 2 secondi con ricentramento sul baricentro del traffico.
* **Layout Aperto & Bandierine Nazionali**: Mappa e feed live visibili contestualmente all'apertura; tabella con bandierine nazionali accanto ad entrambi i nominativi (`TX` e `RX`). Rimosso il pulsante superfluo Fast Add QSO da WSJT-CB.

---

## Versione 3.1.0 (Build 40) - Settembre 2026

### Novità e Miglioramenti
* **Dati Certi e Reali al 100% da Database (Plugin 58)**: Rimossa qualsiasi simulazione o nominativo fittizio. Mappa, tabelle e grafici interrogano direttamente le tabelle del server (`archivio_collector_da_ft8_retevash`, `archivio_cb_pskreporter_wholeworld` e `/fsp58/v1/feed-graph`).
* **Mappa Diurna Classica Naturale**: Eliminata ogni distorsione o colorazione forzata.
* **Tasto FOCUS con Gestione NO REPORT**: Se l'operatore non ha attività recenti nel database, compare a schermo il messaggio **`NO REPORT`** e l'inquadratura torna al default centrata con zoom sulla zona di traffico.
* **Dashboard FT8 Live Aperta di Default**: Grafico 30 minuti a curve smussate di Bézier cubiche per PSK e XZGroup, e tabella con gli ultimi 10 spot reali che scorrono.

---

## Versione 3.0.9 (Build 37) - Settembre 2026

### Novità e Miglioramenti
* **Mappa Unificata Motore 3.0.2**: Allineamento al motore cartografico delle pagine profilo (`LocatorMapWidget`) con zoom `+` / `-` e panning touch fluido.
* **Switcher Vista**: Visualizzazione flessibile tra SPLIT, MAPPA a tutto schermo e TABELLA a tutto schermo.
