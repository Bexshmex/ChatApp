# ChatApp 💬

Realtime chatová aplikace vytvořená pomocí React, Zustand, Socket.io‑client a Axios.

## 🚀 Funkce
- Odesílání a přijímání zpráv v reálném čase  
- Správa stavu aplikace přes Zustand  
- HTTP požadavky a interakce s API pomocí Axios  
- Podpora socket.io‑client pro webové komunikační kanály  

## 🔧 Požadavky
- Node.js v jiné verzi (doporučeno ≥ 16)  
- npm / Yarn / pnpm

## 🧩 Instalace

1. Klonujte repozitář:  
   ```bash
   git clone https://github.com/Bexshmex/ChatApp.git
   cd ChatApp
npm install
npm run build
npm run start

ChatApp/
├── public/               # statické soubory (index.html)
├── src/
│   ├── components/       # React komponenty
│   ├── store/            # Zustand stav (např. useChatStore, useAuthStore)
│   ├── lib/              # např. axios instance
│   └── App.jsx           # hlavní komponenta aplikace
├── package.json
└── vite.config.js

| Skript          | Účel                                    |
| --------------- | --------------------------------------- |
| `npm run dev`   | Spustí vývojový server s hot-reloadem   |
| `npm run build` | Sestaví produkční verzi aplikace        |
| `npm run start` | Spustí produkční build (např. lokálně)  |
| `npm run lint`  | Spustí lintování kódu (pokud nastaveno) |
| `npm run test`  | Spustí testy (pokud jsou napsané)       |

npm install zustand socket.io-client axios

