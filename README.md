# Travel Journal

A simple, dependency-free static website documenting my travels — built with plain HTML and CSS, no frameworks and no build step. Fast to load, easy to host anywhere.

🌐 **Live site:** [adamtadros.dev](https://adamtadros.dev)

## About

This is a personal travel journal: a photo-driven journal of places I've been, kept intentionally lightweight. The whole thing is static HTML, which means it loads instantly, has no dependencies to maintain, and can be deployed to any static host.

- `index.html` — the main travel journal page
- `gallery.html` — photo gallery
- `images/` — photography from the trips

## Why plain HTML?

No build tooling, no framework, no JavaScript bundle to ship. For a content site like this, hand-written semantic HTML keeps it fast, portable, and simple to maintain — and it's a good reminder that you don't always need a framework.

## Running locally

Because it's just static files, you can open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is deployed via Firebase Hosting.

```bash
firebase deploy
```
