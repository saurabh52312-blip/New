# A Letter, and a Question 💌

A small, self-contained romantic invitation website. One HTML file, no backend, no build step — open it in a browser and it just works.

## What it does

The site walks through five short "acts":

1. **The envelope** — a wax-sealed envelope opens with an animated flap when tapped.
2. **The letter** — a handwritten-style message that reveals line by line, ending in the ask: *"Will you go on a date with me?"* The "No" button is intentionally locked and just teases back.
3. **The forever message** — a short, sequential reveal of lines about wanting more than just one date.
4. **Plan the date** — pick a vibe (quiet & cozy / dinner / adventure), then fill in a date, time, location, and optional note.
5. **The ticket** — a wax-stamped "confirmed" ticket summarizing the plan, with a share button that pops a little burst of kisses before opening the device share sheet (or copying the details to your clipboard).

Ambient gold and wine-colored specks drift gently across the whole page throughout.

## Files

- `index.html` — the entire site (HTML, CSS, and JavaScript in one file)
- `README.md` — this file

## Running it locally

Just double-click `index.html`, or open it directly in any browser. No installation needed.

## Hosting it for free (GitHub Pages)

1. Create a new **public** GitHub repository.
2. Upload `index.html` to it (filename must stay exactly `index.html`).
3. Go to **Settings → Pages**, set Source to "Deploy from a branch," branch `main`, folder `/ (root)`, then Save.
4. Wait about a minute, then refresh that page — your live link will appear, something like:
   `https://yourusername.github.io/your-repo-name/`
5. To make future edits, click the file in GitHub, hit the pencil icon, change the text, and commit — the live page updates automatically.

## Personalizing it

Open `index.html` and search for the comments marked `<!-- ✏️ personalize -->`. Those mark the two spots written generically on purpose:

- The opening paragraph of the letter
- The "reasons why" list

Swap them out for something real and specific between the two of you — that's the part that will actually land.

## Notes

- No data is stored or sent anywhere; everything runs in the visitor's browser.
- Works on both desktop and mobile, including the native share sheet on supported devices.
- Built with Google Fonts (Cormorant Garamond, Work Sans, Caveat) loaded over HTTPS — an internet connection is needed the first time for the fonts to load and cache.
