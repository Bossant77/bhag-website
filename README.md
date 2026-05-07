# BHAG — Make your own website

Final project for **Procesos Creativos** (UAM / Holberton).
Static personal site about Big Hairy Audacious Goals.

## Stack

Pure **HTML / CSS / JavaScript**. No frameworks, no libraries, no build step.

## Pages

- `index.html` — homepage + smart thumbnail
- `goals.html` — list of BHAGs
- `about.html` — about Santiago
- `tweets.html` — embedded tweet
- `styles.css` — custom styling (overrides Holberton `school.css`)
- `behavior.js` — smart thumbnail click toggle

## Structure (every page)

```
body
  header   → div.right (share buttons) + ul nav (logo + links)
  main     → article + aside
  footer   → "Made by Santiago for Holberton School"
```

Layout: CSS Flexbox.
- `body` → column
- `main` → row, `flex: auto`
- `article` → `flex: 2`
- `aside` → `flex: 1`

## Run locally

Open `index.html` in any browser.

## Deploy

Hosted via GitHub Pages at:
`https://bossant77.github.io/bhag-website/`

## TODO

- [ ] Replace `<p>placeholder...</p>` in every `<aside>` with Disqus Universal Code (after registering shortname at disqus.com)
