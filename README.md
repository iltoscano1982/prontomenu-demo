# ProntoMenu — PWA demo ristorante

Demo gratuita con menù, categorie, carrello, calcolo totale, composizione ordine WhatsApp, manifest e service worker. Nessun backend, nessun pagamento, nessuna prenotazione confermata. Dati e attività inventati.

## Pubblicazione da iPhone
1. Crea su GitHub un repository pubblico **prontomenu-demo** (non modificare OneChat).
2. Carica nella radice del repository `index.html`, `app.js`, `config.js`, `manifest.webmanifest`, `sw.js`, `README.md` e nella cartella `icons` i due PNG.
3. In Settings → Pages seleziona Deploy from a branch, `main`, `/ (root)` e Save.
4. Visita `https://TUO-USERNAME.github.io/prontomenu-demo/` dopo la pubblicazione.
5. Da Safari su iPhone: Condividi → Aggiungi alla schermata Home → Aggiungi.

## WhatsApp
In `config.js` sostituisci `whatsappNumber: ''` con il numero autorizzato dell'attività in formato internazionale, ad esempio `393331234567` (numero solo illustrativo, non usare). Finché il campo è vuoto, l'app non invia messaggi a terzi: copia soltanto il testo dell'ordine. L'utente deve confermare l'invio dentro WhatsApp.

## Personalizzazione
Modifica nomi, prezzi e categorie in `app.js`; testi e stile in `index.html`; nome e numero in `config.js`; nome e colori nel manifest. Per vedere aggiornamenti dopo la pubblicazione, incrementa il nome CACHE in `sw.js` (es. prontomenu-v2) e ricarica.

## Limiti
Il carrello viene salvato solo sul dispositivo. Le richieste WhatsApp richiedono internet e un numero valido. Nessuna gestione centralizzata degli ordini o pagamenti. Verifica allergeni, prezzi, dati personali, privacy e requisiti legali prima di distribuire a un'attività reale.
