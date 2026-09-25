# Note di Versione - QRZCB Mobile

## Versione 3.0.8 (Build 36) - Settembre 2026

### Novità e Miglioramenti
* **Rifacimento Mappa FT8 Classica e Stabile**: Risolti completamente i problemi di caricamento o rottura delle mappe. Adozione di un sistema di tile con fallback immediato tra OpenStreetMap e ArcGIS World Street Map con filtro Dark Mode nativo: zero errori di connessione e caricamento sempre perfetto.
* **Terminatore Solare (Day/Night) Sempre Visibile di Default**: Calcolo matematico in tempo reale UTC della declinazione del Sole (basato su `nightday.js` di Frank Service Pack 58). L'alternanza tra giorno e notte sulla Terra è ora visualizzata permanentemente con sfumatura d'ombra e linea crepuscolare azzurra, senza bisogno di attivazioni manuali nel menu Layer.
* **Gestione Stazione Utente ("Me Stesso") & Casetta**:
  - Se l'utente non ha effettuato o ricevuto QSO FT8 nell'intervallo temporale selezionato, non viene mostrato come finto spot attivo.
  - Al primo avviso o toccando l'icona casetta, viene richiesta esplicita conferma all'utente per mostrare la casetta della propria stazione (dedotta dal locator/GPS). Se confermata, appare una discreta icona a casetta verde; se non confermata, non viene mostrato nulla.
* **Pulizia TopBar**: Rimossa la label lampeggiante `UPDATE` dalla barra superiore accanto al numero di versione.
* **Conferma Funzionalità Tattiche Mappa**: Tasto FOCUS, rotante temporale (`15m` -> `30m` -> `1h` -> `12h` -> `24h`), protezione server a 10 richieste/min con banner `TOO MUCH REQUEST`, e 4 tendine a scomparsa (Feed, Layers, Ricerca, Legenda).

---

## Versione 3.0.7 (Build 35) - Settembre 2026

### Novità e Miglioramenti
* **Mappa FT8 27Mhz Interattiva Avanzata**: Tasto FOCUS, tasto rotante orari, linee vettoriali di collegamento QSO, rate-limiting server a 10 req/min e marker differenziati (XZGroup/VASH, PSK-Reporter, utenti registrati QRZCB con 'W').
* **Feed Verticale Social**: Formato verticale per le schede con sfocatura automatica delle bande superiore e inferiore per le immagini eQSL orizzontali.
* **Profilo Esterno & My eQSLs**: Badge `nickname_cb` azzurrino integrato anche nei profili cercati e restyling coerente della pagina `My eQSLs`.

---

## Versione 3.0.6 (Build 34) - Settembre 2026

### Novità e Miglioramenti
* **Menu Drawer Riorganizzato**: La prima voce è ora `Profile`, seguita da `My eQSLs` e `FT8 27Mhz MAP`.
* **eQSL Intere nel Profilo & Mini-Profili**: Rimosso qualsiasi taglio sulle eQSL con mini-profilo operatore e messaggio `NO eQSL yet!`.
* **Perfezionamenti Ricerca Nominativi**: Suggerimenti limitati a max 5 risultati e avatar dark-mode pulito per utenti senza foto.

---

## Versioni Precedenti

### Versione 3.0.5 (Build 33)
* Dati certi al 100% da database ufficiale.
* Filtro feed per foto profilo e stazione popolate.
* Nuova scheda utente spotlight.

### Versione 3.0.4 (Build 32)
* Card utente verticale a scorrimento nel feed.
* Riquadro eQSL nel profilo a doppia colonna.
