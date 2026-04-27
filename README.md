# HSK 1 Mandarin Flashcards

A beautiful, interactive flashcard app for learning Mandarin Chinese based on the HSK 1 syllabus. No installation needed — it runs entirely in your browser.

**Live Demo:** [https://YOUR_USERNAME.github.io/hsk1-flashcards](https://YOUR_USERNAME.github.io/hsk1-flashcards)

## Features

- **150 HSK 1 vocabulary words** organized by category
- **Interactive flashcards** with flip animation
- **Audio pronunciation** using built-in text-to-speech
- **Visual Quiz** — match characters to meanings
- **Listening Quiz** — hear the word, pick the meaning
- **Browse Mode** — explore by category
- **Progress tracking** with keyboard shortcuts

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Name your repository `hsk1-flashcards`
3. Make it **Public**
4. Click **Create repository**

### Step 2: Upload the Files

On the repository page:

1. Click **"uploading an existing file"**
2. Drag and drop `index.html` and `README.md` from this folder
3. Click **Commit changes**

Or using the command line:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/hsk1-flashcards.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings**
2. Scroll down to the **Pages** section (or click **Pages** in the left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose **Branch: main** and **Folder: / (root)**
5. Click **Save**

Your site will be live at:

```
https://YOUR_USERNAME.github.io/hsk1-flashcards
```

It may take 1–2 minutes to deploy.

### Optional: Use a Custom Domain

1. In the repository, go to **Settings > Pages**
2. Under **Custom domain**, enter your domain (e.g., `flashcards.yourdomain.com`)
3. Add a `CNAME` file to your repository containing just your domain name
4. Configure DNS with your domain provider

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| Left Arrow | Previous card |
| Right Arrow | Next card |
| Space / Enter | Flip card |
| A | Replay audio |

## Tech Stack

- Pure HTML, CSS, and JavaScript — no build step required
- Web Speech API for Mandarin pronunciation
- Single-file architecture for easy hosting
