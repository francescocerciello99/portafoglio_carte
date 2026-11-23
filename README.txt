PORTAFOGLIO CARTE — VERSIONE PWA

CONTENUTO
- index.html: applicazione
- manifest.webmanifest: impostazioni installazione
- sw.js: cache offline
- icons/: icone app

DATI E PRIVACY
Questa versione salva i dati in localStorage sul browser/dispositivo.
I dati non vengono sincronizzati automaticamente tra dispositivi.
Usa "Esporta backup" periodicamente e conserva il file JSON in un posto sicuro.
"Importa backup" sostituisce i dati presenti con quelli del backup selezionato.
Non inserire mai numero completo della carta, CVV o PIN.

PUBBLICAZIONE GRATUITA
Per installarla su iPhone come PWA devi pubblicare questa cartella su un hosting HTTPS statico
(ad esempio GitHub Pages). Poi apri l'indirizzo con Safari > Condividi > Aggiungi alla schermata Home.
L'installazione PWA e il service worker richiedono HTTPS (oppure localhost).

NOTA
L'app può funzionare offline dopo il primo caricamento riuscito e dopo che il service worker
ha installato la cache. I Google Fonts richiedono Internet; offline verranno usati i font di sistema.
