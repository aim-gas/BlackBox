# Changelog

All notable changes to BlackBox are documented in this file.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Save / load workspaces
- OCR for scanned PDFs
- Additional ML algorithms

## [12.0.0] — 2026-05

### Added
- **© gas.ac** wordmark in top-right of the app in brand-blue accent.

### Changed
- PowerPoint exports no longer carry a per-slide copyright line — decks are clean.

## [11.0.0] — 2026-05

### Added
- **PowerPoint export** (`.pptx`) — fully editable, native PPT charts with data labels, KPI cards, column statistics table, raw-data tables, pivot view, ML pipeline results, embedded GDPR / privacy slide.
- **Word export** (`.doc`) — editable cover, insights, KPI cards, chart images + accompanying data tables, raw data, GDPR notice.
- Per-tab quick-export and master "Download Deck" buttons in the topbar.

## [10.0.0] — 2026-05

### Added
- **PDF support** — upload multiple PDFs, extract text in-browser via PDF.js, dedicated "Document" tab with page navigator, **Chat with Document** using the configured LLM, export extracted text as `.txt`.

## [9.x] — 2026-05

### Added
- GDPR-compliant privacy modal (Articles 15 / 16 / 17 / 20 / 25 / 32) with gas.ac copyright.
- Outlined-only BlackBox wordmark on the loader / sidebar / upload-hero, with thin variant for small font sizes.

### Fixed
- Temporal-dead-zone error that caused the application to halt before features could load.

## [7.x] — 2026-04

### Added
- Multi-sheet Excel support with hierarchical sidebar grouping.
- "Entire File" tab — cross-sheet summary + pivot across sheets.
- ML pipeline — regression / classification with train-test split and drift report.

## [6.x] — 2026-03

### Added
- Initial public-ready release.
- File formats: CSV, XLSX, XLS, DOCX, JSON, TXT, TSV.
- Auto dashboards, drag-and-drop pivot, AI Chat (BYO key), Email Alerts, theme toggle, GDPR data wipe.
