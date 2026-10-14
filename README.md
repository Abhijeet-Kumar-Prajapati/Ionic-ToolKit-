# 📂 Ionic ToolKit

**All-in-One Student Tools Application**

Calculator, Library Management, Snake Game, DSA Visualizer, Matrix Operations, Coding Platform, AI Chat aur Browser — sabhi tools ek hi application mein.

> Pure HTML, CSS aur JavaScript me likha gaya. Koi framework, koi build step, koi installation nahi.

---

## 🧰 Features

Har tool ke **do versions** hain — ek **Basic** (simple) aur ek **Advanced** (extra features ke saath).

| Tool | Kya karta hai |
|---|---|
| 🧮 **Calculator** | Memory buttons (M+, M−, MR, MC, MS), DEG/RAD mode, trig functions (`sin`, `cos`, `tan`), `n!` |
| 📚 **Library Management** | Book add / edit / delete by ID, records dekhna, CSV export |
| 🐍 **Snake Game** | Speed test ke saath — speed badhai ya ghaatao |
| 📊 **DSA Visualizer** | Array operations — new array, reverse, search, step-by-step speed test |
| 🔢 **Matrix Operations** | Add, multiply, transpose, determinant, max/min, scalar × A |
| 💻 **Coding Platform** | Python · JavaScript · C++ problems, Easy / Medium / Hard, run & submit |
| 🤖 **AI Chat** | Built-in chat assistant |
| 🌐 **Browser** | In-app search — Google, YouTube, Wikipedia |

---

## 📥 Download / Install Options

| Device | Recommended |
|---|---|
| 💻 Windows PC/Laptop | Web Version ya source code → `index.html` kholo |
| 🍎 MacBook/iMac | Web Version ya source code → `index.html` kholo |
| 📱 Android Phone | Web Version → "Add to Home screen" / Install app |
| 🌐 Any Device | Web Version |
| 📦 Developer / Student | Source code (git clone) |

### 💻 Windows
Source code download karke extract karo, phir `index.html` double-click kar do. Ya Chrome/Edge me kholo aur **Install app** option use karo.

> `.exe` banane ke liye **Electron + Node** chahiye.

### 🍎 macOS
Source code extract karke `index.html` kholo, ya Chrome/Edge me **Install app**.

> `.dmg` banane ke liye **Electron + macOS** chahiye.

### 📱 Android
`index.html` kholo → Chrome menu (⋮) → **Add to Home screen** / **Install app**.

> Real **APK** banane ke liye **Capacitor / Cordova + Android Studio** chahiye.

### 🌐 Browser (No Installation)
`index.html` koi bhi browser me chalega. **Install app** wala option bhi available hai.

---

## 🚀 Local par chalane ka tarika

Sirf `index.html` open karo — bas. Koi server, koi `npm install`, koi setup nahi.

Ya git se:

```bash
git clone https://github.com/Abhijeet-Kumar-Prajapati/Ionic-ToolKit-.git
cd Ionic-ToolKit-
```

Phir `index.html` open kar do.

---

## 📁 Project Structure

```
Ionic-ToolKit-/
├── index.html                  # Main application (saare tabs)
├── coding_platform.html         # Coding Platform
├── manifest.json               # PWA manifest
├── sw.js                       # Service worker (offline caching)
└── modules/
    ├── calculator.html             # Basic
    ├── calculator_advanced.html    # Advanced
    ├── library.html                # Basic
    ├── library_advanced.html       # Advanced
    ├── snake.html                  # Basic
    ├── snake_advanced.html         # Advanced
    ├── dsa.html                    # Basic
    ├── dsa_advanced.html           # Advanced
    ├── matrix.html                 # Basic
    └── matrix_advanced.html        # Advanced
```

---

## 💡 Important

- Ye ek **PWA** hai — `manifest.json` aur `sw.js` ki wajah se mobile aur desktop dono par **Install app** ka option aa jaata hai.
- **ZIP source package hai.** Sirf ZIP ka naam badalne se `.exe`, `.dmg` ya `.apk` nahi ban jaate — har operating system ke liye alag build tool chahiye (Electron / Capacitor / Android Studio).
- Service worker offline mode ke liye modules cache karta hai, isliye ek baar khulne ke baad bina internet ke bhi kaam karta hai.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript (no framework) |
| App feel | PWA — `manifest.json` + Service Worker |

---

<sub>Made with 💻 by Abhijeet Kumar Prajapati</sub>