# AMW Web — Offline (No Backend)
A fully working **frontend-only** version of A Moment With (Stories → Chapters → Moments) that stores everything **locally** in your browser using **IndexedDB**. No AWS or network required.
## Features
- Create stories, chapters, and moments
- Save images / video / audio as Blobs in IndexedDB
- Preview media inline
- Brand-aligned UI
## Run locally
```bash
npm install
npm run dev
```
Open the URL shown (Vite default is http://localhost:5173).
## Notes
- Data is persisted in your browser. Clearing site data will erase your library.
- This is a drop-in UX prototype you can later connect to your AWS backend.