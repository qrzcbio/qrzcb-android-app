# Note di Versione - QRZCB Mobile

## Versione 3.0.7 (Build 35) - Settembre 2026

### Novità e Miglioramenti
* **Risoluzione Definitiva Mappe ("API requested / Access restricted")**: Eliminata qualsiasi dipendenza da CartoDB. L'intera applicazione adotta tile OpenStreetMap elaborati con una matrice nativa dark-mode (`ColorFilter.matrix`), identica alla logica adottata sul portale web QRZCB (Frank Service Pack 58). Nessuna chiave API, nessun limite, zero schermate di blocco.
* **Mappa FT8 27Mhz Interattiva Avanzata**:
  * **Tasto FOCUS**: Centratura istantanea dell'inquadratura sulla posizione dell'utente collegato, mostrando esclusivamente i suoi contatti nella finestra temporale scelta. Una seconda pressione ripristina la visuale globale con tutti i corrispondenti e imposta il tempo di default a 1 ora.
  * **Selettore Rotante Orari**: Tasto ad anello accanto a FOCUS con rotazione sequenziale rapida tra `15m` -> `30m` -> `1h` -> `12h` -> `24h`.
  * **Linee di Tracciamento QSO**: Collegamento vettoriale curvo tra le stazioni che hanno scambiato spot/QSO.
  * **Rate Limiter Server Protection**: Limite automatico di 10 richieste al minuto per salvaguardare il server. In caso di superamento, viene visualizzato un banner arancione `TOO MUCH REQUEST`, viene impostato un blocco temporaneo di 1 minuto e la finestra oraria torna a 1 ora.
  * **Marker Confermanti**: Quadrato per XZGroup/VASH, cerchio per PSK-Reporter, lettera 'W' per stazioni registrate su QRZCB.io.
* **Badge UPDATE Lampeggiante WhatsApp**: Inserito un badge visivo lampeggiante rosso accanto alla versione nella barra superiore, collegato al supporto WhatsApp (+39 329 328 4302) con richiesta automatica di nuove versioni.
* **Feed Verticale Social**: Formato verticale per le schede con sfocatura automatica delle bande laterali/superiori per le immagini eQSL orizzontali, evitando tagli e preservando l'integrità grafica.
* **Profilo Esterno & My eQSLs**: Badge `nickname_cb` azzurrino integrato anche nella visualizzazione dei profili cercati e restyling della pagina `My eQSLs`.

---

## Versione 3.0.6 (Build 34) - Settembre 2026

### Novità e Miglioramenti
* **Menu Drawer Riorganizzato**: La prima voce è ora `Profile` (accesso istantaneo al proprio profilo), seguita da `My eQSLs` e la nuova voce `FT8 27Mhz MAP`.
* **Nuova Schermata FT8 27Mhz MAP (Frank Service Pack 58)**: Implementata la mappa multilayer FT8 con tema scuro `#070b0f`, accenti teal `#29d9d5`, commutazione rapida Night/Day e 4 tendine a scomparsa chiuse di default.
* **eQSL Intere nel Profilo & Mini-Profili**: Rimosso qualsiasi taglio o cropping superiore/inferiore sulle eQSL ricevute e inviate (`BoxFit.contain`). Inserito sotto ciascuna cartolina un mini-profilo dettagliato dell'operatore e il messaggio pulito `NO eQSL yet!` in assenza di dati.
* **Perfezionamenti Ricerca Nominativi**: I suggerimenti sono rigorosamente limitati a un massimo di 5 record. Gli utenti privi di foto mostrano un elegante avatar dark-mode blu scuro senza caratteri o numeri.
* **Ridenominazione Schermata eQSL**: Titolo della pagina aggiornato in `My eQSLs`.

---

## Versione 3.0.5 (Build 33) - Settembre 2026

### Novità e Miglioramenti
* **Dati Certi e Allineati dal Database Reale**: Rimosso qualsiasi valore presunto o generato. Nel feed e nella ricerca, tutti i dati degli operatori provengono al 100% dal database ufficiale QRZCB.
* **Filtro Rigoroso Feed**: Gli utenti appaiono nel feed solo se hanno sia la foto profilo che la foto della stazione radio (`foto_equipment`) popolate e valide.
* **Nuova Scheda Utente Spotlight**: Immagine di copertina stazione radio a tutto campo, avatar ingrandito con bandiera nazione sovraimpressa in basso a destra, nominativo grande, nome operatore, badge `nickname_cb` con bordo azzurro e box statistiche con confermati/totale e percentuali (LOOKUPS, QSO, FT8).
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
