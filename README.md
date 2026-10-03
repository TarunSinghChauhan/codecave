# MY CODECAVE

Crack the code. Paste any Python or JavaScript and Sensei explains it line by line, in simple words, and can read the explanation out loud.

**Live site:** https://trustcodecave.vercel.app

## What it does
- **Ask Sensei:** paste your code, choose your level, optionally ask a question, and get a plain-English walkthrough.
- **Listen:** Sensei reads the explanation aloud using your browser's built-in voice.
- **Hover effects:** the home page title rebuilds itself as BUILT BY TARUN out of small code pieces.

## How it's built
- Plain HTML, CSS and JavaScript
- A small serverless function (`api/explain.js`) that calls Google's Gemini API
- Hosted free on Vercel

## Setup
Add `GEMINI_API_KEY` as an environment variable in Vercel, then redeploy. Never put the key in the code.

Built by Tarun.
