# AD Community Research Assistant

A research chatbot grounded in Alzheimer's Disease community forum data (forum.alzheimers.org.uk).

## Setup

1. Open `index.html` and replace `YOUR_ANTHROPIC_API_KEY_HERE` with your Anthropic API key
2. Deploy to GitHub Pages (see below)

## Deployment (GitHub Pages)

1. Push this repo to GitHub
2. Go to repo **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your app will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## Data

- **19,383 forum threads** from the Alzheimer's Society UK community forum
- Sourced from `talkpoint1.json` through `talkpoint10.json`
- `data/index.json` — pre-built search index (headings + snippets) loaded at startup
- Full thread files available in `data/` for reference

## Features

- 🫂 **Community Member** persona — warm, peer-like, lived-experience tone
- 🔬 **AD Expert** persona — clinical, research-analytical tone
- Keyword search retrieves the 15 most relevant threads per query
- Conversation history maintained within each session

## For Research Use Only
