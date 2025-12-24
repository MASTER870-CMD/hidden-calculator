# 🔐 Dual Vault Calculator App

![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-3-blue?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=black)

A hidden **calculator-based secure vault application** built as a **single HTML file** using pure frontend technologies.

---

## 📌 Overview

This project is a **one-file web application** that looks like a normal calculator but secretly unlocks a private vault when a secret code is entered.

Everything — **HTML, CSS, and JavaScript** — exists inside **one file: `index.html`**.  
No backend, no frameworks, no external dependencies.

---

# 📲Preview & demo screen shot (face 1)

 <img width="264" height="381" alt="Screenshot 2025-12-24 092543" src="https://github.com/user-attachments/assets/437026e5-b97d-4655-9307-94bfbedf395e" />


## 🧠 How It Works

1. Open `index.html` in a browser
2. Calculator UI is shown
3. Enter numbers normally
4. Enter secret code → press `=`
5. Calculator hides
6. Vault UI appears with files and notes

---
# 📲Preview & demo screen shot (face 2)
<img width="1361" height="636" alt="Screenshot 2025-12-24 095840" src="https://github.com/user-attachments/assets/b73634cd-e3c8-4c76-9ed8-2a2d8ff88eba" />

---

## ✨ Features

### 🧮 Calculator
- Basic arithmetic operations
- Delete and clear functions
- Calculation history (stored locally)
- Triple-click display to view history

### 🔑 Secret Code Access
- Default secret code: `9999`
- Stored in LocalStorage
- Can be changed inside the vault
- Wrong code keeps calculator active

### 📁 Secure Vault
- Hidden behind calculator UI
- Smooth slide animation
- Tab-based layout

### 🗂️ File Management
- Drag & drop uploads
- Click-to-upload support
- Auto sorting:
  - Images
  - Videos
  - Documents
- Preview in modal
- Delete files individually

### 📝 Text Notes
- Built-in text editor
- Notes stored locally
- Auto-loaded on vault open

### 🗄️ Storage System
- **IndexedDB** → files
- **LocalStorage** → secret code, history, notes

---

## 🧰 Technologies Used

| Technology | Purpose |
|---------|--------|
| HTML5 | Structure |
| CSS3 | Styling & animations |
| JavaScript (ES6) | Application logic |
| IndexedDB | Local file storage |
| LocalStorage | Settings & data |

---

## 📂 Project Structure

index.html


✔ Single file only  
✔ No folders  
✔ No assets directory  
✔ No external libraries  

---

## 🚀 How to Run

1. Download `index.html`
2. Open it in any modern browser
3. Use calculator
4. Enter secret code → press `=`
5. Vault opens

---

## 🌐 Browser Compatibility

- Chrome
- Edge
- Firefox
- Brave
- Opera

> IndexedDB must be enabled

---

## 🔐 Security Notes

- Client-side only
- Data stored in browser storage
- No encryption applied
- Clearing browser data deletes vault data
- Not for high-security use

---

## ⚠️ Limitations

- No cloud sync
- No login system
- Browser-dependent storage
- No cross-device access

---

## 📌 Use Cases

- Personal hidden storage
- Offline private files
- Study notes
- Frontend demo project
- Security-through-obscurity demo

---

## 📜 License

MIT License

---

## 👤 Author

**Shashank Gowda NB**  
Fullstack Developer &  Eathical hAcker
