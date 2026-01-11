# 🌐 Plantar Flower — Website Template

A starter template for the **Plantar Flower Website**, used by Website Developers to build:

- Supabase authentication  
- Login system (Email + Password, GitHub, Google, Apple)  
- Game embedding  
- Pine Coin UI  
- User dashboard  
- Responsive layout  
- Communication with the Game Developer API  

This repository is designed to be cloned and extended by Website Developers working on the Plantar Flower project.

---

## 📁 Folder Structure

~~~text
/
├── public/
│   ├── index.html
│   ├── icons/
│   └── assets/
│
├── src/
│   ├── auth/
│   │   ├── supabase.js
│   │   ├── login.js
│   │   ├── session.js
│   │   └── logout.js
│   │
│   ├── game/
│   │   ├── loadGame.js
│   │   ├── apiBridge.js
│   │   └── ui/
│   │       ├── pineCoins.js
│   │       └── gameContainer.js
│   │
│   ├── pages/
│   │   ├── login.html
│   │   ├── dashboard.html
│   │   └── play.html
│   │
│   ├── styles/
│   │   ├── main.css
│   │   └── login.css
│   │
│   └── utils/
│       └── helpers.js
│
├── package.json
├── LICENSE
└── README.md
~~~

---

## 🔐 Authentication (Supabase)

Supports four login methods:

- Email + Password  
- GitHub  
- Google  
- Apple  

All powered by **Supabase Auth**.

---

## 🎮 Game Integration

- Loads `gameBundle.js` from the Game Developer Template Repo  
- Connects to the game API:  
  - `startGame()`  
  - `pauseGame()`  
  - `loadData()`  
  - `saveData()`  
- Displays Pine Coins  
- Embeds the game canvas  
- Fully responsive  

---

## 🛠️ Getting Started

### 1. Clone the repository
git clone https://github.com/Planter-flower-Team/Plantar-flower-website-template

### 2. Install dependencies
npm install

### 3. Add Supabase credentials  
Create a `.env` file:
VITE_SUPABASE_URL=your-url-here
VITE_SUPABASE_ANON_KEY=your-anon-key-here

### 4. Run the development server
npm run dev

### 5. Connect the game bundle  
Place `gameBundle.js` (provided by Game Developers) in:
/public/assets/game/

### 6. Deploy  
Deploy using Vercel, Netlify, GitHub Pages, or your preferred platform.

---

## 🤝 Collaboration With Game Developers

Website Developers must coordinate with Game Developers to receive:

- Supabase URL + anon key  
- gameBundle.js updates  
- API changes  
- Version updates  

---

## 📄 License

This project is licensed under the **MIT License**.
