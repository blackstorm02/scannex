# Scannex

Scannex is a Next.js app that evaluates misinformation risk across pasted text, article URLs, and uploaded images. It produces a structured risk report with red flags, verification steps, a neutral rewrite, and a concise summary.

## Getting started

```bash
git clone https://github.com/nybzmr/scannex.git
cd scannex
npm install
npm run dev
```

The development server runs on [http://localhost:3001](http://localhost:3001).

## Environment

Create a `.env` file with:

```bash
GEMINI_API_KEY=your_api_key_here
```

## Features

- Text, URL, and image scanning
- Gemini-based risk analysis with fallback handling
- Verification checklist for review workflows
- Share-safe rewrite generation

## Maintainer

Nayaab Zameer

## Scripts

```bash
npm run dev
npm run build
npm run start
npm run lint
```
