# Docker-Ops-Arena

A self-contained, single-file interactive Docker quiz and practice web app built with a **Container Mission Control (Bento HUD)** UI, **Light/Dark theme** support, and `localStorage` auto-save/resume.

## Key Features
* **420 Curated Docker Questions** across **7 domains** (`IMG`, `CNT`, `DFB`, `NET`, `VOL`, `CMP`, `SEC`).
* **3 Sequential Tiers (`Basic` → `Intermediate` → `Advanced`):** Complete each tier to unlock the next one per domain.
* **Two Modes:** **Arena Run** (live quiz gameplay with score, streak, and timer) and **Question Bank** (browse and revise questions and explanations).
* **Auto-Save & Resume:** Progress is saved automatically in browser `localStorage` so you can continue from where you left off.
* **Zero Setup:** Runs as a single HTML file (`docker-ops-arena.html`) with no backend or build step required.

## Open Directly in Browser via GitHub Pages
1. Upload `docker-ops-arena.html` (or `index.html`) to your GitHub repository (e.g., `Docker-Ops-Arena`).
2. Open the repository **Settings** tab and click **Pages** in the left sidebar.
3. Under **Build and deployment → Branch**, select `main` (or `master`) and folder `/ (root)`, then click **Save**.
4. Wait a moment for GitHub to generate your live URL:
   `https://<username>.github.io/<repo>/docker-ops-arena.html` (or `https://<username>.github.io/<repo>/` if using `index.html`).
5. Click the live link to open and play directly in your browser.

## Run Locally
Download `docker-ops-arena.html` and double-click it to open it directly in any modern web browser.
