# Note di Versione - QRZCB Mobile

## Versione 3.0.5 (Build 33) - Settembre 2026

### Novità e Miglioramenti
* **Dati Certi e Allineati dal Database Reale**: Rimosso qualsiasi valore presunto o generato. Nel feed e nella ricerca, tutti i dati degli operatori (Lookups, QSO, percentuali di conferma, FT8, nominativi, nickname CB e città) provengono al 100% dal database ufficiale QRZCB.
* **Filtro Rigoroso Feed**: Gli utenti appaiono nel feed solo se hanno sia la foto profilo che la foto della stazione radio (`foto_equipment`) popolate e valide. Gli eventi passati sono esclusi (mostrati solo quelli in corso o futuri).
* **Nuova Scheda Utente Spotlight**: Immagine di copertina stazione radio a tutto campo, avatar ingrandito con bandiera nazione sovraimpressa in basso a destra, nominativo grande, nome operatore, badge `nickname_cb` con bordo azzurro e box statistiche con confermati/totale e percentuali (LOOKUPS, QSO, FT8).
* **Mappa FT8 con Mappa Reale Dark Mode & Sovraimpressione di Test**: Integrazione mappa reale Dark Mode a piastrelle (CartoDB Dark Matter) senza API esterne, con scritta `(MAPPA DI TEST)` e rimozione dei collegamenti simulati.
* **Suggerimenti Casuali nella Ricerca**: Dopo i risultati cercati da un utente (fino a 5), compaiono sempre suggerimenti casuali degli ultimi operatori registrati dalla community.
* **Miglioramenti Barra Superiore**: Click sul logo o sul titolo per tornare al proprio profilo; rimossi i pixel LED e riorganizzati gli stati su due righe allineate a destra (`USER: xx - DEMO : xx` e `WEB - QRZCB - DB`).

---

## Versioni Precedenti

### Versione 3.0.4 (Build 32)
* Card utente verticale a scorrimento nel feed.
* Predisposizione schermata FT8 Live Map e Fast Add QSO.
* Riquadro eQSL nel profilo a doppia colonna (Ultima Ricevuta e Ultima Mandata).
* Riorganizzazione menu laterale con link GitHub e nota informativa di avviso beta.

### Versione 3.0.3 (Build 31)
* Telemetria e indicatori 24 ore per utenti e sessioni demo.
* Feed multimediale dinamico con eQSL, utenti e diplomi.
* Semplificazione menu e navigazione silenziosa.

### Versione 3.0.2 (Build 30)
* Accesso rapido demo e monitor connettività a tre indicatori.
