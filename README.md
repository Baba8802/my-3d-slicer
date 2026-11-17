MY 3D SLICER — PROTOTIPO V1.0
================================

COSA FUNZIONA
- PWA installabile dalla schermata Home di iPad (servita via HTTPS).
- Dashboard con Bambu Lab P1S e Anycubic Kobra X.
- Importazione STL binario e ASCII.
- Visualizzazione 3D interattiva con rotazione e zoom.
- Calcolo dimensioni X/Y/Z.
- Archivio locale IndexedDB di filamenti e profili.
- Esportazione del file STL originale.
- Cache offline dell'app dopo il primo caricamento.

COSA NON È ANCORA IMPLEMENTATO
- Motore di slicing WebAssembly e generazione G-code.
- Importazione 3MF.
- Connessione diretta LAN/cloud alle stampanti.
- Controllo stampa, webcam e monitoraggio.
Non inviare file generati da questo prototipo alla stampante: non genera G-code.

INSTALLAZIONE
1. Pubblicare il contenuto della cartella su un hosting HTTPS statico (es. GitHub Pages o Cloudflare Pages).
2. Aprire l'indirizzo con Safari su iPad.
3. Toccare Condividi > Aggiungi alla schermata Home.
4. Aprire l'icona MY 3D SLICER.

NOTE
I profili macchina sono valori iniziali di progetto: verificare sempre le specifiche e i parametri reali della propria macchina prima dell'integrazione del motore di slicing.
I dati di materiali e profili sono conservati nel database locale del browser/dispositivo.
