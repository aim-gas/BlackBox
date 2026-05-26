<div align="center">

# BlackBox — Know Your Data Pulse

**AI-powered, privacy-first data intelligence — runs entirely in your browser.**

[![License: MIT](https://img.shields.io/badge/License-MIT-2756a8.svg)](LICENSE)
[![Live Demo](https://img.shields.io/badge/demo-live-22c55e.svg)](https://aim-gas.github.io/BlackBox/)
[![No Server](https://img.shields.io/badge/server-zero-8AB4F8.svg)](#privacy)
[![GDPR](https://img.shields.io/badge/GDPR-compliant-22c55e.svg)](PRIVACY.md)
[![Single File](https://img.shields.io/badge/single--file-HTML-f59e0b.svg)](#install)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-ec4899.svg)](CONTRIBUTING.md)

Upload a spreadsheet, a PDF, or a Word doc — get instant dashboards, AI-generated insights, an interactive pivot table, an ML pipeline, and a chat interface for your documents. **No upload. No server. No tracking. Nothing leaves your browser.**

</div>

---

## ✨ Features

| | |
|---|---|
| 📊 **Auto Dashboards** | Drop a file, get charts, KPIs, and statistics in seconds |
| 📝 **AI Insights** | Plain-English findings extracted from your data |
| 🔄 **Drag-and-Drop Pivot** | Excel-style pivot table — no row/column limits |
| 🤖 **ML Pipeline** | Train regression/classification models on your data with one click |
| 📕 **Chat with PDFs** | Upload policy docs / contracts / papers — ask questions, get answers |
| 💬 **AI Chat** | Bring your own OpenAI / Anthropic / Gemini / local LLM key |
| 📋 **Multi-Sheet Excel** | Hierarchical sidebar, per-sheet + cross-sheet analysis |
| 📁 **Many Formats** | CSV · XLSX · XLS · DOCX · PDF · JSON · TXT · TSV |
| 📤 **Export** | Editable **PowerPoint** decks with native charts · Editable **Word** docs · CSV |
| 🔔 **Email Alerts** | Set thresholds, get notified (EmailJS) |
| 🌓 **Dark / Light** | Theme toggle |
| 🔒 **GDPR-Native** | Art. 15 / 17 / 20 supported in-app; one-click "Wipe All Data" |

---

## 🚀 Quick Start

### Option 1 — Try it instantly (recommended)

[**→ Open the live demo**](https://aim-gas.github.io/BlackBox/)

That's it. No install, no signup. Drop a file and go.

### Option 2 — Run locally

```bash
git clone https://github.com/aim-gas/BlackBox.git
cd BlackBox
# Open index.html in any modern browser
open index.html       # macOS
xdg-open index.html   # Linux
start index.html      # Windows
```

That's it. **No npm install. No build step. No backend.** BlackBox is a single self-contained HTML file.

### Option 3 — Self-host

```bash
# Any static file server works:
python3 -m http.server 8000
# → http://localhost:8000
```

Drop `index.html` on any CDN, S3 bucket, GitHub Pages, Vercel, Netlify, or your intranet. It just works.

---

## 🔒 Privacy <a id="privacy"></a>

BlackBox is **fully client-side**. There is no backend, no telemetry, no analytics SDK, no tracking cookie, no remote log. Every uploaded file is parsed and analysed inside the browser's sandbox — bytes never leave the device.

The only outbound traffic — and only when you explicitly enable it — is the LLM API call you configure in Settings, sent under your own credentials to the provider you choose.

See [PRIVACY.md](PRIVACY.md) for the full GDPR notice (Articles 15, 16, 17, 20, 25, 32).

---

## 🎬 Screenshots

> _Add screenshots here after first publish:_
>
> - `docs/screenshots/dashboard.png`
> - `docs/screenshots/pivot.png`
> - `docs/screenshots/pdf-chat.png`
> - `docs/screenshots/ml-pipeline.png`

---

## 🧠 AI Chat — Bring Your Own Key

BlackBox supports any OpenAI-compatible LLM endpoint:

- OpenAI (GPT-4, GPT-4o, etc.)
- Anthropic Claude (via proxy)
- Google Gemini
- Groq / Together / Fireworks
- Local llama.cpp / Ollama / LM Studio

Configure in **⚙ Settings → AI Chat**. Your key is stored in `localStorage` on your device only.

---

## 📤 Export Options

| Format | Editable | Includes |
|---|---|---|
| **PowerPoint (`.pptx`)** | ✅ Native PPT objects | Cover, AI insights, KPIs, **native editable charts** with data labels, column stats, raw data, pivot, ML results, GDPR notice |
| **Word (`.doc`)** | ✅ Fully editable | Cover, insights, KPIs, chart images + data tables, raw data, pivot, GDPR notice |
| **CSV** | ✅ | Active dataset |
| **Text (`.txt`)** | ✅ | Extracted PDF text |

---

## 🛠 Tech Stack

- **Vanilla HTML / CSS / JS** — no framework, no build tool
- [Chart.js](https://www.chartjs.org/) — visualisations
- [SheetJS](https://sheetjs.com/) — Excel parsing
- [PapaParse](https://www.papaparse.com/) — CSV parsing
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) — Word parsing
- [PDF.js](https://mozilla.github.io/pdf.js/) — PDF parsing
- [PptxGenJS](https://gitbrent.github.io/PptxGenJS/) — PowerPoint generation
- [EmailJS](https://www.emailjs.com/) — alert delivery (optional)

All loaded from CDN. **Zero npm dependencies.**

---

## 🤝 Contributing

Issues, feature requests, and pull requests are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) first.

---

## 🗺 Roadmap

- [ ] Save / load workspaces
- [ ] Custom dashboard layouts
- [ ] More ML algorithms (XGBoost in WASM, K-Means)
- [ ] OCR for scanned PDFs
- [ ] Plugin system for custom analyses
- [ ] PWA / offline-first
- [ ] Embedded mode (iframe API)

---

## 📜 License

[MIT](LICENSE) — free for personal and commercial use. See [TRADEMARKS.md](TRADEMARKS.md) for brand-name guidance.

---

## 💙 Credits

Built with care by **[gas.ac](https://gas.ac)**.
"BlackBox", the cube logo and the EKG pulse identity are trademarks of gas.ac — see [TRADEMARKS.md](TRADEMARKS.md).

If BlackBox saved you time, please ⭐ star the repo — it's the cheapest way to say thanks.
