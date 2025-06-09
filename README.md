# 🌃 Night Racing Multiplayer (Firebase)

A browser-based multiplayer 3D racing game where you and up to 6 friends can race and chill in a neon-lit night city — no backend server needed. Built with **Three.js** and **Firebase Realtime Database**.

---

## 🚗 Features

- 🔥 Multiplayer (up to 6 players)
- 🌃 Night city roads & glowing buildings
- 🎮 Arrow key driving controls
- 🛠️ Firebase for real-time car sync
- 🖥️ Runs in any browser, no install
- 🌐 Host it anywhere (GitHub Pages, Netlify, Firebase)

---

## 📦 How to Use

1. Clone or download this repo
2. Open `index.html` in your browser
3. Share the file or host it online to play with friends!

---

## 🔧 Firebase Setup

1. Go to [https://console.firebase.google.com](https://console.firebase.google.com)
2. Create a new project (any name)
3. Add a web app to the project
4. Copy your Firebase config and paste it into `index.html` like this:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  databaseURL: "https://YOUR_PROJECT.firebaseio.com",
  projectId: "YOUR_PROJECT",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
