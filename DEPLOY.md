# 🚀 Guida Rapida al Deploy su GitHub Pages

## Passi per pubblicare il sito

### 1. Crea la Repository su GitHub

1. Vai su [GitHub](https://github.com)
2. Clicca su **New repository** (o il pulsante **+** in alto a destra)
3. Nome repository: `dionosio1`
4. Scegli **Public** (necessario per GitHub Pages gratuito)
5. **NON** inizializzare con README, .gitignore o licenza (li abbiamo già)
6. Clicca **Create repository**

### 2. Carica i File

#### Opzione A: Usando Git (raccomandato)

```bash
# Nella cartella del progetto
git init
git add .
git commit -m "Initial commit - Dionisio's Napulitan Barbery"
git branch -M main
git remote add origin https://github.com/TUO-USERNAME/dionosio1.git
git push -u origin main
```

#### Opzione B: Upload Manuale

1. Vai sulla repository appena creata
2. Clicca su **uploading an existing file**
3. Trascina tutti i file: `index.html`, `styles.css`, `script.js`, `README.md`, `.gitignore`
4. Clicca **Commit changes**

### 3. Attiva GitHub Pages

1. Nella repository, vai su **Settings** (in alto)
2. Scorri fino a **Pages** (menu laterale sinistro)
3. In **Source**, seleziona:
   - Branch: `main` (o `master`)
   - Folder: `/ (root)`
4. Clicca **Save**

### 4. Il tuo sito è online! 🎉

Il sito sarà disponibile a:
**https://TUO-USERNAME.github.io/dionosio1/**

*Nota: può richiedere 1-2 minuti per essere attivo*

## ✅ Verifica

1. Vai all'URL del tuo sito
2. Controlla che tutte le sezioni siano visibili
3. Testa la navigazione e le animazioni
4. Verifica su mobile (responsive)

## 🔧 Personalizzazioni Post-Deploy

Dopo il deploy, puoi modificare:
- Contatti (indirizzo, telefono, email) in `index.html`
- Coordinate della mappa Google Maps
- Prezzi dei servizi e prodotti
- Colori e stili in `styles.css`

Ogni modifica richiede un nuovo commit e push:

```bash
git add .
git commit -m "Descrizione modifica"
git push
```

## 📝 Note

- GitHub Pages supporta solo siti statici (HTML, CSS, JS)
- I file devono essere nella root della repository
- Il file principale deve chiamarsi `index.html`
- Le modifiche possono richiedere alcuni minuti per essere visibili

---

**Buon deploy! 🎊**

