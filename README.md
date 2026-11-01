# Serialo – Palestra e Passi

App di allenamento in palestra con contapassi per smartphone Android e smartwatch Wear OS (Pixel Watch e simili).

Gratis, senza pubblicità, senza account ([informativa](PRIVACY.md)).

## Scarica
Apri **[l'ultima versione](https://github.com/vincenzociriello91-hub/Serialo-download/releases/latest)** e scarica:
- `Serialo-telefono.apk` → per lo smartphone
- `Serialo-solo-per-orologio.apk` → per lo smartwatch

Telefono e orologio hanno sempre lo stesso numero di versione: usa sempre la stessa su tutti e due.

## Installa sul telefono
1. Scarica `Serialo-telefono.apk` dal telefono.
2. Aprilo e consenti l'installazione da questa fonte se Android lo chiede.
3. Al primo avvio concedi il permesso **Attività fisica** per i passi.

**Aggiornamenti sul telefono:** ogni volta che apri Serialo o ci torni (al massimo ogni 15 minuti) controlla se c'è una versione nuova: te lo dice da solo, ti mostra le novità e, se vuoi, la installa **sopra** quella che hai. Schede e storico restano.

## Installa sull'orologio
Gli APK per Wear OS non si aprono toccandoli: vanno inviati all'orologio via debug wireless.
1. Sull'orologio: Impostazioni → Sistema → Info → tocca 7 volte **Numero build** per attivare le Opzioni sviluppatore.
2. Impostazioni → Opzioni sviluppatore → attiva **Debug ADB** e **Debug wireless**, poi **Accoppia nuovo dispositivo**: compaiono IP, porta e codice.
3. Sul telefono usa un'app di installazione ADB per Wear OS (dal Play Store) e invia `Serialo-solo-per-orologio.apk` con i dati mostrati dall'orologio.
4. Apri Serialo sull'orologio e concedi **Sensori del corpo** (battito) e **Attività fisica** (passi).

**Aggiornamenti sull'orologio:** l'orologio non si aggiorna da solo. Quando esce una versione nuova ripeti i passi 2 e 3 con il nuovo `Serialo-solo-per-orologio.apk`: si installa sopra e le serie salvate restano. Se hai Serialo dal Play Store, l'orologio si aggiorna dal Play Store.

## Come si usa
- **Telefono**: modifica le schede (Giorno A, B, C) o caricale da foto/PDF e tocca *Invia schede all'orologio*. Qui vedi passi, storico, record e peso corporeo.
- **Orologio**: scegli il giorno, regola carico e ripetizioni con − e +, tocca *Fatta* (o lascia contare le ripetizioni al polso). Parte il recupero, con vibrazione e avviso vocale alla fine.
- Funziona anche senza telefono vicino: le serie arrivano al telefono quando si ricollega.
- In fondo alla schermata **Oggi** del telefono: Novità, Suggerimenti, rapporti anonimi e *Controlla aggiornamenti*.

Le novità di ogni versione sono in [NOVITA.md](NOVITA.md) e nella pagina Novità dell'app.

## Rapporti anonimi, solo se vuoi
Al primo avvio Serialo chiede se può inviare rapporti tecnici quando qualcosa va storto (chiusure improvvise, sincronizzazione con l'orologio, lettura della scheda). Mai allenamenti, peso, passi, battito, posizione o schede. Si spengono quando vuoi. Dettagli nell'[informativa](PRIVACY.md).

## Suggerimenti e problemi
Dall'app: in fondo alla schermata Oggi › **Suggerimenti e problemi**, oppure [apri una segnalazione](https://github.com/vincenzociriello91-hub/Serialo-download/issues/new?template=suggerimento.yml). La pagina è pubblica: non scrivere dati di salute.

## Informazioni
- [Informativa sulla privacy](PRIVACY.md)
- © 2026 Vincenzo Ciriello. Questo repository contiene solo l'app compilata: il codice sorgente non è pubblico.
