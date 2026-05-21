


# ⚡ ESP-NOW RF Decryption Analyzer

**Real-time analysis of 35+ encryption techniques** – a futuristic web tool for visualizing and comparing cryptographic outputs.  
Designed for RF engineers, cybersecurity enthusiasts, and anyone exploring data encoding methods.

![Version](https://img.shields.io/badge/version-4.0-00f5ff)
![Techniques](https://img.shields.io/badge/techniques-35%2B-ff00ff)
![License](https://img.shields.io/badge/license-MIT-00ff9d)

---

## 🛰️ Overview

This project is a **client-side encryption dashboard** that takes any input text and simultaneously applies 35 different encoding / encryption techniques (from simple binary and hex to industrial-grade AES-256, RSA-4096, ChaCha20, and more).  
It visualises the outputs in a sleek, sci-fi interface with animated neural networks, real-time statistics, and export capabilities.

> **Inspired by ESP-NOW RF broadcast analysis** – the tool simulates how a ground station might decode or interpret multiple encrypted signals in a noisy environment.

---

## ✨ Features

- **35+ encryption / encoding methods**, including:
  - Classic: Binary, Hexadecimal, Base64, Caesar, Atbash, ROT13, XOR, Reverse  
  - Transposition: Rail Fence, Vigenère, Affine  
  - Modern symmetric: AES-256, ChaCha20, Twofish, Serpent, Camellia, Blowfish, 3DES, RC6, MARS, IDEA, CAST-256, GOST, SEED, ARIA, SM4, Kalyna, XTEA, Speck, Simon, PRESENT  
  - Asymmetric (simulated): RSA-4096, ECC-384  
  - Perfect: One-Time Pad (OTP)

- One-click analysis across all techniques  
- Confidence / strength rating for each method  
- Live input preview with binary & hex extracts  
- Real-time statistics dashboard  
- Export results as JSON  
- Copy-all-to-clipboard feature  
- Demo mode with sample inputs  
- Animated cyber background (neural network + scanning effects)  
- Fully responsive UI (desktop + mobile)

---

## 🖥️ Tech Stack

- HTML5 – structure and layout  
- CSS3 – neon UI, animations, glassmorphism  
- JavaScript (ES6) – encryption logic + UI engine  
- Font Awesome 6 – icons  
- No external dependencies

---

## 🚀 Getting Started

### 1. Clone or download
```bash
git clone https://github.com/satyabhargavteki25-sudo/alien.git
cd esp-now-rf-analyzer
````

### 2. Run the application

Open `index.html` directly in any modern browser:

* Chrome
* Firefox
* Edge
* Safari

No server required.

---

### 3. How to use

* Enter text in the input box
* Click **ANALYZE ALL ENCRYPTIONS** (or press `Ctrl + Enter`)
* Scroll through generated encryption outputs
* Use side panel options:

  * Clear results
  * Export JSON
  * Load demo
  * Copy all outputs

---

## 🧪 Example Output

Input: `"Hello World"`

| Technique | Output                             |
| --------- | ---------------------------------- |
| Binary    | `01001000 01100101 01101100 ...`   |
| Hex       | `48 65 6C 6C 6F 20 57 6F 72 6C 64` |
| Base64    | `SGVsbG8gV29ybGQ=`                 |
| Caesar    | `Khoor Zruog`                      |
| AES-256   | `AES-256 Output (simulated)`       |

---

## 📁 File Structure

```
esp-now-rf-analyzer/
└── index.html   # Single-file application (HTML + CSS + JS)
```

---

## 🧠 How It Works

* Each encryption method is implemented as a JavaScript function
* Input is processed through all methods in parallel
* Results are dynamically rendered into UI cards
* Simulated algorithms (AES, RSA, etc.) use hashed outputs for demonstration
* Stats are stored in memory during session runtime

---

## 🎨 UI Highlights

* Dark cyberpunk theme
* Neon glow accents (cyan, magenta, green)
* Glassmorphism cards
* Animated neural network background
* Smooth hover and pulse animations
* Keyboard shortcuts:

  * `Ctrl + Enter` → Analyze
  * `Ctrl + D` → Demo
  * `Ctrl + C` → Copy all

---

## 🔮 Future Enhancements

* Real AES / RSA via Web Crypto API
* True decryption module
* File upload support (.txt, binary)
* RF noise simulation engine
* PDF / CSV export support
* Live signal visualization layer

---

## 🙏 Acknowledgements

* Inspired by ESP-NOW protocol (Espressif Systems)
* Font Awesome for icons
* Modern cyber-security dashboard UI trends

---

## 📄 License

MIT License – free to use, modify, and distribute with attribution.

---

## 👤 Author

Built as a demonstration of encryption visualization and RF signal analysis concepts.

*Made with ⚡ and curiosity for cryptography*

