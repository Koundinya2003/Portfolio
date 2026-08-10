# Aditya K. Koundinya — Portfolio

Product portfolio for **Aditya K. Koundinya** — AI Product · Product Analytics.

**Live:** https://reliable-pithivier-8680e0.netlify.app/

## Stack

A single static page. No framework, no build step, no dependencies, no tracking.

```
index.html      the whole site (inline CSS + ~70 lines of vanilla JS)
assets/         résumé PDF, Open Graph image
_redirects      Netlify: legacy /aditya_portfolio.html → /
```

## Local preview

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Deploy

Netlify serves `index.html` from the repository root — no build command, publish
directory `.`. The same layout works unchanged on GitHub Pages or Vercel.

## Editing

All content lives in `index.html`, in section order: hero, about, product thinking,
selected work, AI depth, experience, product case studies, skills, education, contact.
Replacing `assets/Aditya-K-Koundinya-Resume.pdf` updates every résumé link on the page.
