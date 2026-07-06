# Apex Music Worx

The official website for **Apex Music Worx**, a professional music studio offering
recording, mixing, mastering, and production services.

Built as a fast, lightweight static site (HTML, CSS, and vanilla JS) — no build
step required.

## Structure

```
apex-music-worx/
├── index.html     # Page content and structure
├── styles.css     # All styling
├── script.js      # Mobile nav + contact form demo handler
├── .replit        # Replit run/deploy configuration
└── README.md
```

## Run locally

Because it's a static site, you can open `index.html` directly in a browser, or
serve it with any static server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy on Replit

1. Push this project to GitHub.
2. In Replit, create a Repl by importing the GitHub repo.
3. Replit reads `.replit` and serves the site; use **Deploy → Static** to publish.

## Editing content

- **Text, sections, links:** `index.html`
- **Colors, fonts, layout:** `styles.css` (theme colors live in `:root` at the top)
- **Interactions:** `script.js`
