# 🌐 MemePedia: The Free Meme Encyclopedia

> A retro Wikipedia-style timeline documenting the evolution of classic internet memes, complete with embedded video previews, interactive search, and responsive MediaWiki styling.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Hosting](https://img.shields.io/badge/hosted%20on-Vercel%20%2F%20GitHub-black)

---

## 📌 Overview

**MemePedia** is a lightweight, single-file static web application designed to mirror the classic MediaWiki (Wikipedia Vector theme) layout. It presents a chronological timeline of viral internet history from the mid-1990s onward, featuring embedded video playback, responsive design, and instant search capabilities.

Built with **pure HTML, CSS, and vanilla JavaScript**, it has zero dependencies and requires no build steps—making it instantly hostable via **GitHub Pages** and **Vercel**.

---

## ✨ Features

- **Authentic Wikipedia UI**: Styled after MediaWiki with classic typography, sidebar navigation, headers, and color palettes.
- **Chronological Timeline**: Visual vertical timeline organizing iconic internet milestones by year.
- **Embedded Video Previews**: Built-in 16:9 responsive YouTube embeds for direct playback of classic meme videos.
- **Instant Live Search**: In-page JavaScript filter that screens timeline entries in real time.
- **Quick Jump Navigation**: Sidebar anchor links for smooth jumping directly to specific eras/years.
- **Zero Dependencies**: Pure static code for maximum performance and fast initial load times.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic document structure
- **CSS3**: MediaWiki Vector styling, responsive flexbox layout, and CSS timeline nodes
- **JavaScript (ES6+)**: Real-time DOM filtering for quick search
- **Deployment**: Compatible with GitHub Pages & Vercel

---

## 🚀 Deployment Instructions

### Option 1: Deploy to Vercel (Recommended)

1. Push your `index.html` file to a GitHub repository.
2. Go to [Vercel](https://vercel.com) and click **Add New Project**.
3. Import your GitHub repository.
4. Keep all default build settings (no build command or output directory needed for static HTML).
5. Click **Deploy**.

### Option 2: Deploy to GitHub Pages

1. Push your repository to GitHub.
2. Go to your repository settings: **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

---

## 📁 Repository Structure

```text
.
├── index.html   # Main application file (UI, styling, scripts, and meme entries)
└── README.md    # Project documentation
