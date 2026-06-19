# 🪨 CSV Vault Viewer

A single-page, 100% offline-first, client-side CSV spreadsheet dashboard inspired by the dark mode aesthetic of Obsidian. It reads and parses multiple local CSV files simultaneously without requiring any local backend server, node compilation, or internet connectivity.

---

## 🚀 Key Features

- **100% Offline Capable:** Built entirely with embedded CSS and standard Web API structures. No internet connection or remote CDN calls are required once assets are downloaded.
- **Multi-File Workspace:** Select and load multiple CSV datasets at once (or append them incrementally) to toggle between files instantly using a sticky sidebar tree navigation layout.
- **Fast Client-Side Parsing:** Powered by **PapaParse** for fast processing of heavy data documents directly inside the sandbox of your browser container.
- **Real-Time Global Filter:** Instant multi-column search filter functionality that limits row visual states on-the-fly as you type.
- **Zero-Server Security Core:** Data strictly lives in the volatile memory space of your browser environment. Your files are never uploaded to any remote network server, cloud stack, or backend process, ensuring full data privacy.

---

## 📂 Vault Structure

To maintain complete offline security optimization, organize your working directory as follows:

```text
csv-vault-viewer/
├── index.html          # Main application engine with embedded layout styling
└── papaparse.min.js    # Local core parsing module dependencies