# Longman Construction: homepage concept

A redesigned homepage concept for **Longman Construction Company Inc.**, custom home builders in Newport Beach, California (CSLB 393881, established 1980).

**Live concept:** https://oakspin-ai.github.io/longman-construction-homepage/

Prepared by OakSpin AI as a design concept. It is not the company's official website.

## What changed versus the current site, and why

| Current site | This concept |
|---|---|
| Fixed desktop-width layout that scales down to tiny type on a phone | Fully responsive: readable type, a slim mobile menu and a fixed "Call Neil" bar |
| Blue backgrounds and serif navigation from an older theme | Calm fog-and-navy palette; the logo's own steel blue is the single accent |
| Home page is one paragraph and a logo | A clear opening: what Longman builds, where, and who leads it |
| Service labels link to `#` and go nowhere | Services are plain text, and the page ends with a working inquiry form (opens an email to Neil with the details filled in) and a tap-to-call number |
| Project galleries sit on separate inner pages | Named projects by neighborhood and architectural style, plus interiors, on the homepage |
| Credentials and press are easy to miss | Credentials as large numerals (1980, 65 homes, license 393881, 5 islands); press listed with its publications |
| Small, hard-to-find contact details | Phone and "Start a conversation" in the header on every screen |

The one bold element is the Longman logotype set large and filled with a photograph of one of their homes.

## Facts and photos

All copy traces to longmanconstruction.com (home, About, Portfolio and Press pages) and the CSLB record for license 393881. Photos are Longman's own project photos from their site; no stock or generated images. Their source files are small (mostly 700 to 942 px wide), so the page uses layouts that don't stretch them.

## Run locally

```bash
python3 -m http.server 8743
# then open http://localhost:8743
```

Single static `index.html` with inline CSS and a little vanilla JS; images are in `assets/img/`.
