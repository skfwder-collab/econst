# Siwat Teimtad - Economist Portfolio

> *"Master Economics, the Simple Way."*

A modern, responsive portfolio website built with a sleek dark aesthetic, typography powered by **JetBrains Mono**, and in-depth economic research projects. Designed for seamless hosting on **GitHub Pages**.

---

## 🚀 Live Demo & Structure

- **Homepage**: [`index.html`](index.html) — Hero with quote, bio, contact details (`dx@outlook.com`), and curated research previews.
- **Projects**:
  1. [`projects/economics-in-one-lesson.html`](projects/economics-in-one-lesson.html) — *Key economic concepts of Economics in One Lesson written by Henry Hazlitt in 1946* (~1,690 words).
  2. [`projects/game-theory.html`](projects/game-theory.html) — *Game Theory: Strategic Interaction, Equilibrium Concepts, & Mechanism Design* (~1,630 words).
- **Styles**: [`style.css`](style.css) — Custom modern dark theme using JetBrains Mono, CSS variables, and reading progress indicators.
- **Scripts**: [`script.js`](script.js) — Interactive one-click email copying, toast notifications, back-to-top navigation, and scroll progress tracking.
- **Logo**: [`black.png`](black.png) — Monogram branding asset.

---

## 🛠 Local Preview

To preview the website locally on your computer:

```bash
# Using Python's built-in HTTP server:
python -m http.server 8000
```
Then open your browser to `http://localhost:8000`.

---

## 🌐 Deploy to GitHub Pages (Step by Step)

### Step 1: Initialize Git and Commit
```bash
git init
git add .
git commit -m "feat: complete economist portfolio with Hazlitt and Game Theory projects"
```

### Step 2: Push to GitHub
1. Create a new repository on [GitHub](https://github.com/new) (e.g. `my-portfolio` or `<your-username>.github.io`).
2. Run the following commands in your terminal:
```bash
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** > **Pages** (in the left-hand sidebar).
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`, Folder: `/(root)`
4. Click **Save**.

Your portfolio will be live at:
```text
https://<your-username>.github.io/<your-repo-name>/
```
