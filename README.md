# PixelCode 🔐
> *"Privacy is not about hiding — it's about owning what is yours."*

A browser-based tool that converts any image into an **AES-256 encrypted text code** — and decodes it back. No uploads. No servers. No traces.

## 🌐 Live Demo
**[Try it here → pixelcode-saiacharya.netlify.app](https://pixelcode-saiacharya.netlify.app/)**

## ✨ Features
- 🔒 AES-256-GCM encryption (military-grade)
- 🔑 PBKDF2 key derivation — 310,000 iterations with SHA-256
- 🎲 Random 32-byte salt + 12-byte IV per encryption (every code is unique)
- 🖼️ Drag & drop image encoding with live preview
- 📄 Download encrypted code as `.txt` file
- 📂 Decode by dropping the `.txt` file back in
- 💻 Zero-dependency — single HTML file, no frameworks, no backend
- 🚫 Nothing ever leaves your device

## 🛡️ How It Works
1. Drop an image → set a password → click **Encrypt**
2. Get a `PIXELCODE:v2:enc:...` text code — completely unreadable without the password
3. Share the code as a `.txt` file
4. Recipient drops the file → enters the password → image recovered

## 🔧 Tech Stack
- Vanilla JavaScript (ES2020+)
- Web Crypto API (AES-256-GCM + PBKDF2)
- HTML5 File & Drag-and-Drop API
- CSS3 — no frameworks

## ⚠️ Important
The password is never stored anywhere. If you forget it, the image cannot be recovered. This is by design.

## 👤 Author
**Punyamaya Acharya** — [@SaiAcharya00](https://github.com/SaiAcharya00)
