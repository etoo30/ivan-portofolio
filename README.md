# Ivan — Personal Portfolio

Static personal portfolio for Ivan Mulyanto, built with HTML, CSS, and vanilla JavaScript.

## Run locally

From this folder, run:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

The page can also be opened directly as `index.html`. A local server gives the most reliable results for fonts and links.

## Project files

- `index.html` — portfolio content and metadata.
- `assets/css/style.css` — visual system and responsive layout.
- `assets/js/main.js` — mobile navigation, active section, reveal behavior, current year.
- `assets/img/` — favicon and locally stored editorial coffee photographs.
- `photo-credits.html` — required photographer and license attributions.
- `PRODUCT.md` — confirmed product facts and content boundaries.
- `DESIGN.md` — visual system and tokens.

## Photo note

The coffee images are editorial photographs from Wikimedia Commons included in Taste Skill's vetted local library. They illustrate coffee preparation; none is a portrait of Ivan or evidence of a specific workplace. Each image's source, author, and license are listed in `photo-credits.html`. Replace them with Ivan's own work photographs when available, and replace the initials mark with an approved portrait if desired.

Fonts use Google Fonts (Newsreader and DM Sans) with local system fallbacks. Without a network connection, the page remains usable and falls back to Georgia and Arial.
