# Note di Versione - QRZCB Mobile

## Versione 3.0.6 (Build 34) - Settembre 2026

### Novità e Miglioramenti
* **Menu Drawer Riorganizzato**: La prima voce è ora `Profile` (accesso istantaneo al proprio profilo), seguita da `My eQSLs` e la nuova voce `FT8 27Mhz MAP`.
* **Nuova Schermata FT8 27Mhz MAP (Frank Service Pack 58)**: Implementata la mappa multilayer FT8 con tema scuro `#070b0f`, accenti teal `#29d9d5`, commutazione rapida Night/Day e 4 tendine a scomparsa chiuse di default (Plancia Feed in tempo reale, Gestione Layer XZGroup/PSK/Terminatore, Ricerca e Legenda simboli).
* **eQSL Intere nel Profilo & Mini-Profili**: Rimosso qualsiasi taglio o cropping superiore/inferiore sulle eQSL ricevute e inviate (`BoxFit.contain`). Inserito sotto ciascuna cartolina un mini-profilo dettagliato dell'operatore e il messaggio pulito `NO eQSL yet!` in assenza di dati.
* **Perfezionamenti Ricerca Nominativi**: I suggerimenti sono rigorosamente limitati a un massimo di 5 record. Gli utenti privi di foto mostrano un elegante avatar dark-mode blu scuro senza caratteri o numeri. La dicitura `LIMITED to 5 RESULTS` è stata spostata in fondo alla schermata.
* **Ridenominazione Schermata eQSL**: Titolo della pagina aggiornato in `My eQSLs`.

---

## Versione 3.0.5 (Build 33) - Settembre 2026

### Novità e Miglioramenti
* **Dati Certi e Allineati dal Database Reale**: Rimosso qualsiasi valore presunto o generato. Nel feed e nella ricerca, tutti i dati degli operatori (Lookups, QSO, percentuali di conferma, FT8, nominativi, nickname CB e città) provengono al 100% dal database ufficiale QRZCB.
* **Filtro Rigoroso Feed**: Gli utenti appaiono nel feed solo se hanno sia la foto profilo che la foto della stazione radio (`foto_equipment`) popolate e valide. Gli eventi passati sono esclusi (mostrati solo quelli in corso o futuri).
* **Nuova Scheda Utente Spotlight**: Immagine di copertina stazione radio a tutto campo, avatar ingrandito con bandiera nazione sovraimpressa in basso a destra, nominativo grande, nome operatore, badge `nickname_cb` con bordo azzurro e box statistiche con confermati/totale e percentuali (LOOKUPS, QSO, FT8).
* **Mappa FT8 con Mappa Reale Dark Mode**: Integrazione mappa reale Dark Mode a piastrelle (CartoDB Dark Matter) senza API esterne.
* **Suggerimenti Casuali nella Ricerca**: Dopo i risultati cercati da un utente (fino a 5), compaiono suggerimenti casuali degli ultimi operatori registrati dalla community.

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
