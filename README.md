

# 🚀 Cube Share – Peer-to-Peer File Transfer

**Cube Share** is a fast, secure, and modern **peer-to-peer (P2P) file sharing web app** that lets you send files **directly between browsers** using WebRTC — no uploads, no size limits, and no middleman servers.

It features a **glass-morphism UI**, **animated rocket progress**, and works seamlessly across devices.

🌐 **Live Demo:**
👉 [https://shinchanchan.github.io/file_share/](https://shinchanchan.github.io/file_share/)

---

## 🛡️ Badges

[![Hosted on GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?logo=github)](https://shinchanchan.github.io/file_share/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Powered by PeerJS](https://img.shields.io/badge/Powered%20by-PeerJS-blue)](https://peerjs.com/)

---

## ✨ Features

* 🚀 **Direct P2P Transfer** – Browser-to-browser file sharing
* 🔒 **No Server Storage** – Files never touch any backend server
* 🎨 **Glass-Morphism UI** – Modern frosted glass design
* 📊 **Rocket Progress Animation** – Live animated transfer status
* 📁 **Multiple File Support**
* 🖱️ **Drag & Drop Upload**
* 🆔 **One-Click Peer ID Copy**
* 📜 **Real-Time Activity Logs**
* ⏸️ **Pause / Resume Transfer**
* 📱 **Cross-Platform Support** (Desktop & Mobile)
* ❌ **No Login / No Registration**

---

## 🧭 How It Works

```
Sender Browser  ── WebRTC (Direct Transfer) ──► Receiver Browser
        │
        └── PeerJS Server (only for connection setup)
```

1. PeerJS helps peers discover each other
2. WebRTC creates a secure direct connection
3. Files are sent in small chunks
4. Receiver reassembles files automatically

✔️ **Files are encrypted by WebRTC**
✔️ **No data is stored anywhere**

---

## 🚀 Getting Started

### 👤 For Users (3 Simple Steps)

1. **Open the App**

   * Visit [https://shinchanchan.github.io/file_share/](https://shinchanchan.github.io/file_share/)
   * Copy your generated Peer ID

2. **Send Files**

   * Enter the receiver’s Peer ID
   * Select or drag files
   * Click **🚀 Launch Transfer**

3. **Receive Files**

   * Share your Peer ID
   * Files download automatically

---

### 👨‍💻 For Developers

```bash
# Clone the repository
git clone https://github.com/shinchanchan/file_share.git

# Go to project folder
cd file_share

# Run a local server
python3 -m http.server 8000
# OR
npx serve .
# OR
php -S localhost:8000
```

Open 👉 `http://localhost:8000`

---

## 📁 Project Structure

```
file_share/
├── index.html   # Complete app (HTML + CSS + JS)
├── README.md
├── LICENSE
└── .gitignore
```

> ⚡ Entire application runs from a **single HTML file**

---

## 🛠️ Tech Stack

| Technology   | Usage                 |
| ------------ | --------------------- |
| HTML5        | App structure         |
| CSS3         | Glass UI & animations |
| JavaScript   | App logic             |
| WebRTC       | P2P communication     |
| PeerJS       | WebRTC abstraction    |
| GitHub Pages | Hosting               |

---

## 🌐 Browser Support

| Browser         | Support       |
| --------------- | ------------- |
| Chrome          | ✅ Recommended |
| Firefox         | ✅             |
| Edge            | ✅             |
| Safari          | ⚠️ Limited    |
| Mobile Browsers | ✅             |

---

## 🔍 Troubleshooting

| Issue              | Solution                        |
| ------------------ | ------------------------------- |
| Connection error   | Refresh page / re-enter Peer ID |
| Slow speed         | Depends on network              |
| Files not received | Ensure both peers are online    |
| Rocket not moving  | Refresh browser                 |

---

## 🔒 Privacy & Security

* ❌ No file storage
* ❌ No user tracking
* ❌ No login data
* ✅ WebRTC encrypted transfer
* ✅ Direct browser-to-browser sharing

---

### Planned

* 🔐 End-to-End Encryption
* 📈 Speed Indicator
* 👁️ File Preview
* 📷 QR Code Sharing
* 🔄 Resume Failed Transfers
* 🖥️ Electron Desktop App

---

## 📞 Contact & Support

* 📧 **Email:** [vallarasucse200118@gmail.com](mailto:vallarasucse200118@gmail.com)
* 🐞 **Issues:** [https://github.com/shinchanchan/file_share/issues](https://github.com/shinchanchan/file_share/issues)
* 🌐 **Live Demo:** [https://shinchanchan.github.io/file_share/](https://shinchanchan.github.io/file_share/)

---

## 📄 License

Licensed under the **MIT License**
Free for personal & commercial use.

---

## ⭐ Support the Project

If you like this project:

* ⭐ Star the repo
* 🔁 Share with friends
* 🐛 Report issues
* 💡 Suggest features

---

<div align="center">

**Made with ❤️ by vallarasucse200118@gmail.com**

🚀 *Transfer files at the speed of a rocket*

</div>



Just tell me 👍
