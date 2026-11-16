# Final-Year-Project: LocalLens

> 🏆 **Final Year Project** | Privacy-Preserving Offline Language to Visualization | 4-Member Team

A final-year project that turns the faculty patent *"A System and Method for Privacy-Preserving Offline
Language-to-Visualization Conversion"* (specification dated 18.02.2026, included here as a `.docx`) into a working product:
ask a question about your data in plain language, get a chart, with a small language model running entirely on your own machine.

---

## 🎬 Live Demo

> Both demos show the app running **fully offline** — no internet, no cloud, your data never leaves your machine.

---

### 👤 User Side Demo
**What a regular user sees** — asking questions in plain language and getting charts instantly.

https://github.com/Madhurapetare/Final-Year-Project/raw/main/demos/demo2-user-side.mp4

> Click the link above to watch/download the User Side demo.

---

### 🛠️ Admin Side Demo
**What the admin/data owner sees** — uploading datasets, configuring columns, setting business rules.

https://github.com/Madhurapetare/Final-Year-Project/raw/main/demos/demo1-admin-side.mp4

> Click the link above to watch/download the Admin Side demo.

---

## 📁 Project Structure

| | |
|---|---|
| **The product** | [`locallens/`](locallens/) — start there: [`locallens/README.md`](locallens/README.md) |
| **How it works, and how it maps to the patent claims** | [`locallens/docs/ARCHITECTURE.md`](locallens/docs/ARCHITECTURE.md) |
| **How accurate it is (measured on questions it had not seen)** | [`locallens/docs/EVAL.md`](locallens/docs/EVAL.md) |
| **The patent** | `Comp Spec_Privacy-Preserving Offline Language_18.02.2026.docx` |

---

## 🚀 Quick Start

```bash
cd locallens && ./start.sh        # Windows: start.bat   ->  http://127.0.0.1:8000
```

One command installs everything, downloads the AI model (~525 MB, one time only), builds the web app, and starts the server.
