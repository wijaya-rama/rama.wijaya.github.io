# rama.wijaya.github.io

Source code for Rama Wijaya's personal portfolio website, hosted on GitHub Pages.

**Live:** [wijaya-rama.github.io]([https://wijaya-rama.github.io](https://wijaya-rama.github.io/rama.wijaya.github.io/) 
**Archive:** [wijaya-rama.github.io/archive.html](https://wijaya-rama.github.io/archive.html)

## Structure

```text
.
├── index.html       # Main portfolio page
├── archive.html     # Full project archive
├── images/          # Image assets & project thumbnails
├── LICENSE          # MIT License
└── README.md
```

## Tech Stack

- **Markup & Styling:** Semantic HTML5, Tailwind CSS (CDN)
- **Typography:** Plus Jakarta Sans & JetBrains Mono (Google Fonts)
- **Interactions:** Vanilla JavaScript (scrollspy navigation, category filtering)
- **Hosting:** GitHub Pages

## Local Development

The site is built with plain static HTML, CSS, and JavaScript. No build step or package manager is required.

To preview locally:

```bash
# Using Python
python -m http.server 8000

# Or using npx
npx serve .
```

Then open `http://localhost:8000` in your browser.

## License

[MIT](LICENSE)
