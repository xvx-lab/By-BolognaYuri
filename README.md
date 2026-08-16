# BY Bologna Yuri — Sito Web

Sito one-page (con sezioni ancorate) per Yuri Bologna — Tecnico, Commerciale, Bike Specialist. Ravenna, Romagna.

Realizzato a partire dal logo, dalla flyer e dal biglietto da visita del brand: nero, rosso, bianco e accento oro, font "poster" per i titoli.

## Struttura del progetto

```
├── index.html      → struttura e contenuti del sito
├── style.css       → stile, colori, layout, responsive
├── script.js       → menu mobile, anno footer, pulsante "torna su"
├── assets/         → immagini (logo, foto, flyer, QR code)
└── README.md
```

## Sezioni del sito

1. **Hero** — headline "Passione. Energia. Entertainment." con call to action
2. **Chi sono** — presentazione di Yuri Bologna
3. **Servizi** — Eventi & Entertainment, Bike Experience, Escursioni & Tour, Bike Repair
4. **Galleria** — foto e flyer
5. **Contatti** — telefono, WhatsApp, email, indirizzo, social e QR code (link diretti, nessun form)

## Come pubblicarlo su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `bologna-yuri-sito`).
2. Carica tutti i file di questa cartella (`index.html`, `style.css`, `script.js`, cartella `assets/`, `README.md`) nella root del repository.
3. Vai su **Settings → Pages** del repository.
4. In "Branch" seleziona `main` (o `master`) e cartella `/root`, poi salva.
5. Dopo 1-2 minuti il sito sarà online all'indirizzo:
   `https://<tuo-username>.github.io/<nome-repository>/`

## Personalizzazioni rapide

- **Testi**: modifica direttamente in `index.html`.
- **Colori**: cambia le variabili all'inizio di `style.css` (sezione `:root`), es. `--red`, `--gold`.
- **Link social**: aggiorna gli URL reali di Instagram/Facebook/YouTube nella sezione `#contatti` di `index.html` (attualmente Instagram punta a `@bologna_yuri`, Facebook e YouTube sono segnaposto da collegare ai profili reali).
- **Numero/email**: aggiorna `tel:`, `https://wa.me/` e `mailto:` nella stessa sezione.

## Note tecniche

- Nessuna dipendenza esterna oltre ai font Google (Anton + Inter), caricati via CDN.
- Nessun form di contatto: i pulsanti aprono direttamente telefono, WhatsApp, email.
- Completamente responsive (desktop, tablet, mobile) con menu a scomparsa su schermi piccoli.
