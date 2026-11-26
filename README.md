# Docker-Ops-Arena

A self-contained, single-file interactive Docker quiz and practice web app built with a **Container Mission Control (Bento HUD)** UI, **Light/Dark theme** support, and `localStorage` auto-save/resume.

## Key Features
* **420 Curated Docker Questions** across **7 domains** (`IMG`, `CNT`, `DFB`, `NET`, `VOL`, `CMP`, `SEC`).
* **3 Sequential Tiers (`Basic` → `Intermediate` → `Advanced`):** Complete each tier to unlock the next one per domain.
* **Two Modes:** **Arena Run** (live quiz gameplay with score, streak, and timer) and **Question Bank** (browse and revise questions and explanations).
* **Auto-Save & Resume:** Progress is saved automatically in browser `localStorage` so you can continue from where you left off.
* **Zero Setup:** Runs as a single HTML file (`docker-ops-arena.html`) with no backend or build step required.

## Ways to Open & Play in Browser

### 1. GitHub Pages (Direct Live Link)
1. Upload `docker-ops-arena.html` (or `index.html`) to your GitHub repository.
2. Go to repository **Settings → Pages**.
3. Under **Build and deployment → Branch**, select `main` (or `master`) and `/ (root)`, then click **Save**.
4. Open the generated live URL in your browser (`https://<username>.github.io/<repo>/docker-ops-arena.html` or `https://<username>.github.io/<repo>/` if using `index.html`).

### 2. Fork & Enable GitHub Pages
1. Click **Fork** at the top-right of this repository to copy it to your GitHub account.
2. In your forked repository, go to **Settings → Pages**.
3. Under **Build and deployment → Branch**, choose `main` (or `master`) and `/ (root)`, then click **Save**.
4. Open your published GitHub Pages link (`https://<your-username>.github.io/<repo>/docker-ops-arena.html` or `https://<your-username>.github.io/<repo>/`).

### 3. Run Locally (Double-Click in Browser)
1. Download or save `docker-ops-arena.html` onto your computer.
2. Open File Explorer and **double-click** `docker-ops-arena.html` to launch it directly in your browser.

### 4. Netlify Drop (Instant Drag & Drop Hosting)
1. Save `docker-ops-arena.html` (or `index.html`) in a folder on your computer.
2. Open **Netlify Drop** in your browser and drag-and-drop the file or folder.
3. Click the instant live URL provided to open the app in your browser.
