
# 🚀 Cube File’s Share

**Cube File’s Share** is a modern, fast, and secure **peer-to-peer (P2P) file sharing web app** built with **WebRTC**.
It allows users to transfer files **directly between devices** without uploading to any server — **no compression, no size limits, no middleman**.

🔐 **Your files stay private.**
⚡ **Transfers are lightning fast.**
🎨 **UI is clean, modern, and beautiful.**

---

## 🌐 Live Demo

👉 **Try it here:**
🔗 [https://shinchanchan.github.io/file_share/](https://shinchanchan.github.io/file_share/)

---

## ✨ Key Features

* ✅ **True P2P Transfer** (WebRTC DataChannel)
* ✅ **Zero Server Storage** (no uploads, no tracking)
* ✅ **Original Quality Preserved** (bit-perfect transfer)
* ✅ **Glass-morphism UI** with space theme
* ✅ **Rocket Progress Animation 🚀**
* ✅ **Multiple File Transfer**
* ✅ **Drag & Drop Support**
* ✅ **Clipboard Copy for Peer ID**
* ✅ **Real-time Activity Logs**
* ✅ **Pause / Resume Transfers**
* ✅ **Cross-Platform Support** (Desktop & Mobile)
* ✅ **No Login / No Signup**

---

## 🖼️ Screenshots

| Home Screen                                                            | Transfer in Progress                                                                |
| ---------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| ![UI](https://via.placeholder.com/400x250/0f0c29/ffffff?text=Glass+UI) | ![Progress](https://via.placeholder.com/400x250/302b63/ffffff?text=Rocket+Progress) |

---

## 🚀 How to Use (3 Simple Steps)

### 1️⃣ Get Your Peer ID

* Open the app
* Copy your auto-generated ID (example: `P2P-4821`)
* Share it with the sender

### 2️⃣ Send Files

* Enter the receiver’s Peer ID
* Select files (or drag & drop)
* Click **🚀 Launch Transfer**

### 3️⃣ Receive Files

* Stay connected
* Files download automatically
* Track progress with rocket animation

---

## 🧑‍💻 Quick Start (Developers)

```bash
# Clone repository
git clone https://github.com/shinchanchan/file_share.git

# Enter directory
cd file_share

# Run locally (any HTTP server)
python3 -m http.server 8000
# or
npx serve .
```

Then open:

```
http://localhost:8000
```

---

## 🗂️ Project Structure

```
file_share/
├── index.html        # Complete app (HTML + CSS + JS)
├── README.md         # Documentation
├── LICENSE           # MIT License
└── .github/          # GitHub workflows (optional)
```

📌 **Single-file architecture**
All UI, logic, and WebRTC handling live inside `index.html`.

---

## 🛠️ Tech Stack

| Technology           | Usage                |
| -------------------- | -------------------- |
| HTML5                | Structure            |
| CSS3                 | Glass UI, animations |
| JavaScript (Vanilla) | App logic            |
| PeerJS               | WebRTC abstraction   |
| WebRTC               | P2P data transfer    |
| GitHub Pages         | Free hosting         |

---

## 🔍 How It Works

```
Sender Browser
      ↓
WebRTC DataChannel (Direct P2P)
      ↓
Receiver Browser

PeerJS Server → Only for signaling (no file data)
```

* PeerJS helps peers discover each other
* Files transfer **directly browser-to-browser**
* Files are sent as **binary chunks**
* Receiver reassembles chunks → original file

✔ No compression
✔ No re-encoding
✔ No quality loss

---

## 🌍 Browser Support

| Browser         | Support                          |
| --------------- | -------------------------------- |
| Chrome          | ✅ Recommended                    |
| Edge            | ✅ Fully supported                |
| Firefox         | ✅ Fully supported                |
| Safari          | ⚠️ Limited (WebRTC restrictions) |
| Mobile Browsers | ✅ Supported                      |

> Best experience: **Chrome / Edge**

---

## 🧯 Troubleshooting

| Issue             | Solution                       |
| ----------------- | ------------------------------ |
| Connection failed | Refresh page, re-check Peer ID |
| Slow speed        | Depends on network quality     |
| Safari issues     | Try Chrome / Firefox           |
| Transfer stuck    | Keep screen awake, reload app  |

---


### Contribution Ideas

* 🔐 End-to-end encryption
* 📷 QR code peer connect
* 📁 Folder transfer
* 📊 Speed meter
* 🔁 Resume broken transfers

---

## 📄 License

Licensed under the **MIT License**

✔ Commercial use
✔ Modification
✔ Distribution
✔ Private use

See [`LICENSE`](LICENSE) for details.

---

## 🔗 Related Projects

* 🔗 [https://peerjs.com/](https://peerjs.com/)
* 🔗 [https://sharedrop.io/](https://sharedrop.io/)
* 🔗 [https://webtorrent.io/](https://webtorrent.io/)

---

## 📬 Contact

* 📧 Email: **[vallarasucse200118@gmail.com](mailto:vallarasucse200118@gmail.com)**
* 🐛 Issues: [https://github.com/shinchanchan/file_share/issues](https://github.com/shinchanchan/file_share/issues)
* 🌐 Live Demo: [https://shinchanchan.github.io/file_share/](https://shinchanchan.github.io/file_share/)

---

<div align="center">

### ⭐ If you like this project, give it a star!

**Made with ❤️ by vallarasu**

[⭐ Star Repo](https://github.com/shinchanchan/file_share) •
[🚀 Live Demo](https://shinchanchan.github.io/file_share/) •
[📧 Contact](mailto:vallarasucse200118@gmail.com)

</div>



Just tell me 👍
