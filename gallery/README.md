# Il Nostro Racconto — Istruzioni

## Struttura del progetto

```
gallery/
├── index.html          ← Pagina principale con le 5 foto
├── pages/
│   ├── foto1.html
│   ├── foto2.html
│   ├── foto3.html
│   ├── foto4.html
│   └── foto5.html
├── images/             ← CREA questa cartella e inserisci le tue foto
│   ├── foto1.jpg
│   ├── foto2.jpg
│   ├── foto3.jpg
│   ├── foto4.jpg
│   └── foto5.jpg
└── README.md
```

## Come aggiungere le foto

### 1. Crea la cartella `images/` e inserisci le tue 5 foto rinominandole:
`foto1.jpg`, `foto2.jpg`, `foto3.jpg`, `foto4.jpg`, `foto5.jpg`

### 2. In `index.html`, per ogni card, sostituisci il blocco `<div class="card-placeholder">...</div>` con:
```html
<img src="images/fotoN.jpg" alt="Foto N">
```

### 3. In ogni file `pages/fotoN.html`, sostituisci il blocco `<div class="photo-placeholder">...</div>` con:
```html
<img src="../images/fotoN.jpg" alt="Titolo foto">
```

### 4. Personalizza i testi in ogni pagina `pages/fotoN.html`:
- Cambia `<h1 class="photo-title">` con il tuo titolo
- Cambia `<p class="photo-subtitle">` con il sottotitolo
- Cambia `<p class="photo-text">` con il tuo testo

## Pubblicare su GitHub Pages

1. Crea un repository su GitHub (es. `il-nostro-racconto`)
2. Carica tutti i file mantenendo la struttura delle cartelle
3. Vai su **Settings → Pages**
4. In "Source" scegli il branch `main`, cartella `/root`
5. Clicca **Save** — il sito sarà online in pochi minuti
6. URL del sito: `https://tuousername.github.io/il-nostro-racconto/`
