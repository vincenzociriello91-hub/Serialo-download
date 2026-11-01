# Informativa sulla privacy di Serialo

Ultimo aggiornamento: 1 novembre 2026

**Serialo non ha account, pubblicità né statistiche d'uso.** I tuoi allenamenti e i tuoi dati restano sul telefono e sull'orologio.

- **Dati di allenamento e salute**: schede, serie, carichi, ripetizioni, peso corporeo, altezza, passi e battito restano sul telefono e sull'orologio. Telefono e orologio se li scambiano direttamente tra loro (Data Layer di Wear OS). Serialo non li invia a nessun server.
- **Health Connect** (telefono): se lo colleghi, Serialo legge i passi e scrive gli allenamenti finiti (con le calorie attive stimate) in Health Connect, sul telefono. Da lì li vedono le app di salute che autorizzi tu (per esempio Fitbit).
- **Posizione della palestra**: la salvi tu una volta; resta sul telefono e serve solo all'avviso quando arrivi in palestra.
- **Foto e PDF della scheda**: il testo si legge sul telefono, senza internet. L'immagine non viene inviata a nessuno.
- **Backup**: «Esporta backup» crea un file che condividi tu, dove vuoi.
- **Aggiornamenti** (telefono): a ogni apertura dell'app, al massimo ogni 15 minuti, Serialo controlla su GitHub se c'è una versione nuova (la versione di Google Play riceve gli aggiornamenti da Google Play). GitHub vede l'indirizzo IP della richiesta, come per qualsiasi pagina web. L'orologio non controlla gli aggiornamenti.
- **Permessi**: attività fisica (passi), sensori del corpo (battito, sull'orologio), Health Connect, posizione anche in background (avviso palestra), notifiche, vibrazione, avvio all'accensione (per riattivare l'avviso palestra), Internet (aggiornamenti e rapporti), installazione di app solo nella versione del telefono scaricata da GitHub, per installare gli aggiornamenti che accetti.
- **Rapporti per migliorare Serialo** (solo se rispondi "Sì, invia" alla domanda del primo avvio sul telefono; la scelta vale anche per l'orologio; si spengono quando vuoi in fondo alla schermata Oggi, *Invia rapporti anonimi*, e spegnendoli si cancellano anche quelli non ancora partiti):
  - *quando*: dopo una chiusura improvvisa dell'app (sul telefono o sull'orologio) e quando la sincronizzazione tra telefono e orologio o la lettura di una scheda da foto/PDF non riesce;
  - *cosa contengono*: se viene dal telefono o dall'orologio, modello del dispositivo, versione di Android, versione di Serialo e da dove l'hai installata (GitHub o Google Play), un codice casuale dell'installazione (non legato a te: cambia se cancelli i dati dell'app), l'errore e il punto del codice in cui è successo;
  - *cosa non contengono mai*: allenamenti, schede (né il testo né i nomi), carichi, ripetizioni, peso, altezza, passi, battito o altri dati di salute, posizione, nomi o indirizzi dei dispositivi, indirizzi IP, account, email o numero di telefono. Dal testo dell'errore Serialo toglie le parti tra virgolette, i numeri con la virgola, gli indirizzi e i percorsi dei file;
  - *come viaggiano*: il rapporto viene cifrato sul dispositivo (AES-256-GCM con una chiave RSA a 3072 bit) prima di partire; passa da un piccolo servizio su Cloudflare, che non lo può leggere e non salva l'indirizzo IP, e finisce in un archivio privato su GitHub. Lo può aprire solo lo sviluppatore di Serialo. L'orologio lo spedisce con la sua connessione (Wi-Fi, rete mobile o quella del telefono collegato);
  - *quanto restano*: il tempo necessario a correggere i problemi; non vengono venduti né condivisi con nessuno;
  - l'ultimo rapporto preparato sul telefono si può leggere in fondo alla schermata Oggi, *Mostra l'ultimo rapporto*.
- **Suggerimenti**: il pulsante apre una pagina pubblica di GitHub con il testo che scrivi tu e il modello del telefono e la versione di Serialo; lo invii tu, con il tuo account GitHub.

Per domande: [apri una segnalazione](https://github.com/vincenzociriello91-hub/Serialo-download/issues).
