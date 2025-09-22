# 🧮 Calcolatore-Z

**Calcolatore-Z** è una web app semplice e veloce per effettuare il calcolo del coefficente di spinta degli interceptor direttamente dal browser. Il calcolo è automatico è non tiene in considerazione delle variabili strutturali dello scafo.

👉 Live demo: https://cthv9.github.io/Calcolatore-Z

[![Install App](https://img.shields.io/badge/⬇️%20Install%20Calcolatore-Z-25D366?style=for-the-badge&logoColor=white)](https://cthv9.github.io/Calcolatore-Z/)


---


## ✨ Funzionalità

- **PWA ready**:
  - Installabile su Android, iOS e desktop;
  - Calcolo del coefficiente Z;
  - Calcolo della spinta in kg a 10 nodi;
  - Funzione per salvare l'immagine;
  - Indicazione di performace (minimo, buono, eccellente)

---

## 🛠️ Struttura del progetto

Calcolatore-Z/
├── index.html # Pagina principale (UI + PWA banner)
├── manifest.json # Configurazione PWA (icone, scope, colori)
├── app.js # Validazioni, redirect
├── service-worker.js # Cache offline e PWA
└── icons/ # Icone PWA
│ ├── favicon.png
│ ├── icon-192.png
│ └── icon-512.png
└── README.md # Questo file


---

## 📲 Come usare

Seleziona il modello interceptor da usare.

Inserisci il numero delle lame da installare.

Clicca su calcola coefficiente per ottenere un risultato dinamico.

---

## 📦 Tecnologie usate


HTML5 / CSS3 responsive

Service Worker

PWA (manifest, offline, icone)

GitHub Pages


---
