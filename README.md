# portfolio

Rajesh's portfolio. Plain HTML, CSS and JavaScript with no build step and no external requests.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Publish on GitHub Pages

Settings → Pages → Source: "GitHub Actions". Every push to `main` runs
`.github/workflows/pages.yml`, which publishes only the site files (not this README).
The site is at https://rchalasani93.github.io/portfolio/

If you add a new file the site needs (an image, another page), add it to the
`cp` line in `pages.yml` too.

## Files

- `index.html` – the page (Home, About, Services, Skills, Projects, Contact)
- `styles.css` – all styles
- `main.js` – mobile menu, active nav link, typing effect
- `404.html`, `robots.txt`, `sitemap.xml`, `og-image.png`, `favicon.svg`
