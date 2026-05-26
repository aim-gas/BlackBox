# Privacy & GDPR Notice

BlackBox is engineered around a single principle: **your data never leaves your device.**

## 1. Local-only processing

All uploaded files (Excel, CSV, Word, JSON, TXT, PDF, unstructured data) are parsed, analysed, summarised, and visualised **entirely within the browser**. No file content, no parsed data, no derived analytics, and no metadata is transmitted to any external server, cloud service, or third party.

## 2. Hosting model

BlackBox is a single self-contained HTML file. You can run it from a local file, host it on your own intranet, or host it on any static-file CDN (GitHub Pages, S3, Vercel, Netlify). There is no telemetry, analytics SDK, tracking cookie, or remote log embedded in the application.

## 3. Optional AI Chat feature

If — and only if — you explicitly enable the AI Chat module and configure your own LLM API key in **⚙ Settings → AI Chat**, the natural-language prompts you type (and a derived summary or extract of the active file) are sent to the LLM provider you selected, **under your own contract and credentials with that provider**. BlackBox itself does not store, intercept, or forward this traffic. Disabling AI Chat returns the tool to fully offline operation.

## 4. No data sharing

There is no shared backend, no multi-tenant database, no analytics provider, no advertising network.

## 5. GDPR compliance — your rights

BlackBox is designed to support compliance with **Regulation (EU) 2016/679** (the General Data Protection Regulation). Because processing happens locally on the data subject's device, the user remains the sole controller of their personal data.

| Article | Right | How it is supported |
|---|---|---|
| Art. 15 | Right of access | All stored data is viewable in the "Raw Data" tab and exportable from Settings → Privacy & GDPR |
| Art. 16 | Right to rectification | Data files may be replaced or re-uploaded at any time |
| Art. 17 | Right to erasure | **"Wipe All Data"** in Settings — permanently deletes every uploaded file, derived analysis, chat history, and configuration value |
| Art. 20 | Right to data portability | **"Export All Data"** in Settings — downloads a portable copy |
| Art. 25 | Data protection by design and by default | Architecture itself prevents server-side processing |
| Art. 32 | Security of processing | Data never leaves the browser sandbox |

## 6. Disclaimer

The software is provided "as is", without warranty of any kind. The user is responsible for verifying analytical outputs before relying on them for any decision-making purpose. gas.ac accepts no liability for losses arising from use of, or inability to use, the software.

## 7. Reporting a privacy concern

If you believe BlackBox has, or could be configured to have, a privacy weakness, please see [SECURITY.md](SECURITY.md) for the responsible-disclosure process.
