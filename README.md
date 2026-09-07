# 🧮 Calcolatore-Z

**Calcolatore-Z** è una web app semplice e veloce per il pre-dimensionamento di interceptor (Serie E / Serie S), direttamente dal browser. Calcola il coefficiente Z secondo una metodologia standard di dimensionamento interceptor e fornisce una stima indicativa della spinta generata.

👉 Live demo: https://cthv9.github.io/Calcolatore-Z

[![Install App](https://img.shields.io/badge/⬇️%20Install%20Calcolatore-Z-25D366?style=for-the-badge&logoColor=white)](https://cthv9.github.io/Calcolatore-Z/)


---


## ✨ Funzionalità

- **PWA ready**:
  - Installabile su Android, iOS e desktop;
  - Calcolo del coefficiente Z (Z = somma lunghezze interceptor / baglio alla chine allo specchio di poppa);
  - Valutazione Minimo / Buono / Eccellente in base alla lunghezza dello scafo;
  - Stima della spinta (kg) a una velocità di riferimento inseribile dall'utente;
  - Consigli automatici: distanza dal target Z = 1, indicazione Serie S/E più adatta, suggerimento delle varianti CHINE dove disponibili;
  - Funzione per salvare il risultato come immagine.

---

## 🛠️ Struttura del progetto

```
Calcolatore-Z/
├── index.html          # Pagina principale (UI, logica di calcolo, PWA banner)
├── manifest.json        # Configurazione PWA (icone, scope, colori)
├── service-worker.js    # Cache offline e PWA
├── icons/                # Icone PWA
│   ├── favicon.ico
│   ├── icon-192.png
│   └── icon-512.png
└── README.md             # Questo file
```

---

## 📲 Come usare

1. Seleziona quante coppie/elementi interceptor installare.
2. Per ciascuna sezione, scegli il modello (Serie E o Serie S) e la quantità.
3. Inserisci lunghezza scafo, baglio alla chine allo specchio di poppa e velocità di riferimento.
4. Clicca su "Calcola Coefficiente" per ottenere Z, valutazione, stima di spinta e consigli.

---

## 📐 Note tecniche sul calcolo

- **Coefficiente Z** e soglie di valutazione seguono una metodologia standard di dimensionamento interceptor: il baglio da inserire è quello **alla chine, misurato allo specchio di poppa**, non il baglio massimo dello scafo.
- Le varianti **CHINE** contribuiscono al calcolo con la lunghezza del modello dritto di taglia superiore nella stessa serie, secondo la regola tecnica per cui un interceptor chine genera una spinta equivalente a un interceptor dritto di taglia superiore.
- La **spinta in kg** è una stima teorica (pressione dinamica sull'area frontale reale delle lame, con un coefficiente di portanza da letteratura idrodinamica, non da dati di produzione) e viene mostrata come intervallo min–max: va presa come ordine di grandezza indicativo, non come dato di progetto.

---

## 📦 Tecnologie usate

HTML5 / CSS3 responsive

Service Worker

PWA (manifest, offline, icone)

GitHub Pages

---
