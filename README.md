# Lucid Author ✦ Minimalist Studio for Authors & Worldbuilders

A distraction-free, privacy-first workspace tailored for novelists, screenwriters, lorekeepers, and worldbuilders. Draft manuscripts in Markdown with Obsidian-style `[[Wiki-Links]]`, sculpt interactive fantasy maps, chronicle multi-era timelines, and visualize story connections with an interactive galaxy graph.

---

## ✨ Features

- **Distraction-Free Markdown Drafting**: Focus-oriented writing environment with typewriter scrolling, customizable typography, and word count sprint goals.
- **Obsidian-Style Wiki-Links**: Interconnect lore, chapters, and entities seamlessly using `[[Entity Name]]` bi-directional syntax.
- **Interactive Map Studio & Universe Atlas**: Multi-tier cartography support for universe, solar systems, planetary maps, continents, and regional territories with custom pins and fog of war.
- **Entity & Character Codex**: Organize protagonists, factions, magic systems, artifacts, and locations with customizable metadata sheets.
- **Chronological Timelines**: Plot non-linear story arcs, historical eras, character lifelines, and parallel plot events visually.
- **Galaxy Graph View**: Dynamic node-network visualization of your entire story universe and entity relationships.
- **100% Private & Offline-First**: All data is stored locally in your browser (IndexedDB / LocalStorage) with one-click JSON/Markdown backup and restore. No telemetry, no external accounts required.
- **Ambient Themes & Soundscapes**: Dynamic ambient backgrounds and audio environments to keep you immersed in your writing flow.

---

## 🚀 Quick Start

### Option 1: Local Development Server

Run the built-in zero-dependency Node.js server:

```bash
# Clone the repository
git clone https://github.com/Nihir-Soni/Lucid-Author.git
cd Lucid-Author

# Start the server
node server.js
```

Open your browser at `http://localhost:8095`.

### Option 2: Run Without Node.js

You can directly open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

---

## 🌐 Deploy to GitHub Pages

This repository includes a pre-configured landing page and web application in the `docs/` folder:

1. Navigate to **Settings** > **Pages** in your GitHub repository (`https://github.com/Nihir-Soni/Lucid-Author/settings/pages`).
2. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
3. Under **Branch**, select `main` and set the folder to `/docs`.
4. Click **Save**. Your site will be live at:
   ```
   https://nihir-soni.github.io/Lucid-Author/
   ```

---

## 📁 Project Structure

```
Lucid-Author/
├── assets/          # App icons, logos, and visual assets
├── build/           # Application build assets
├── css/             # Workspace stylesheets and theme definitions
├── docs/            # GitHub Pages landing page and hosted web app
│   ├── app/         # Web app entry for GitHub Pages
│   ├── assets/      # Landing page media assets
│   └── css/         # Landing page styling
├── js/
│   ├── app.js       # Core application engine, UI controllers, and views
│   ├── markdown.js  # Markdown parser and wiki-link resolver
│   └── storage.js   # Offline storage manager (IndexedDB / LocalStorage)
├── index.html       # Primary application entry point
├── server.js        # Zero-dependency local development server
└── .gitignore       # Git ignore rules
```

---

## 📄 License

This project is licensed under the MIT License - feel free to customize and adapt it for your own creative workflows.

