# Serialo – Palestra e Passi

App di allenamento in palestra con contapassi per smartphone Android e smartwatch Wear OS (Pixel Watch e simili).

## Scarica
Apri **Releases** (a destra in questa pagina) e scarica dall'ultima versione:
- `Serialo-telefono.apk` → per lo smartphone
- `Serialo-solo-per-orologio.apk` → per lo smartwatch

## Installa sul telefono
1. Scarica `Serialo-telefono.apk` dal telefono.
2. Aprilo e consenti l'installazione da questa fonte se Android lo chiede.
3. Al primo avvio concedi il permesso **Attività fisica** per i passi.

## Installa sull'orologio
Gli APK per Wear OS non si aprono toccandoli: vanno inviati all'orologio via debug wireless.
1. Sull'orologio: Impostazioni → Sistema → Info → tocca 7 volte **Numero build** per attivare le Opzioni sviluppatore.
2. Impostazioni → Opzioni sviluppatore → attiva **Debug ADB** e **Debug wireless**, poi **Accoppia nuovo dispositivo**: compaiono IP, porta e codice.
3. Sul telefono usa un'app di installazione ADB per Wear OS (dal Play Store) e invia `Serialo-solo-per-orologio.apk` con i dati mostrati dall'orologio.
4. Apri Serialo sull'orologio e concedi **Sensori del corpo** (battito) e **Attività fisica** (passi).

## Come si usa
- **Telefono**: modifica le schede (Giorno A, B, C) e tocca *Invia schede all'orologio*. Qui vedi passi, storico, record e peso corporeo.
- **Orologio**: scegli il giorno, regola carico e ripetizioni con − e +, tocca *Fatta*. Parte il recupero, con vibrazione e avviso vocale alla fine.
- Funziona anche senza telefono vicino: le serie arrivano al telefono quando si ricollega.

Novità di ogni versione: vedi le note della Release.
