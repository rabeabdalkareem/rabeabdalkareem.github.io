# Academic personal website

A plain HTML/CSS/JS site (no build step, no framework) for a software
engineering professor: About, Research, Teaching, and Students pages.
Built to be hosted for free on GitHub Pages.

## Structure

```
index.html          Home — bio, photo, contact links, research summary
research.html        Research areas + publication list (thumbnail, summary, PDF download)
teaching.html         Teaching philosophy, experience, and course list
students.html         Current and former students, program, research titles
css/style.css        All styling (single stylesheet, shared across pages)
js/main.js            Mobile nav toggle, publication filter, footer year
images/               Your photos and figure thumbnails go here
papers/                Your publication PDFs go here
```

## 1. Customize the content

Everything you need to change is written in plain text in the four `.html`
files — no build tools involved. Search for and replace:

- `Jordan A. Whit` — your name (appears in every page's `<title>`, header brand, and footer)
- `j.whit@university.edu` — your email
- `github.com/yourusername` — your GitHub profile URL
- `scholar.google.com/citations?user=yourid` — your Google Scholar profile URL
- `[University Name]`, `[Doctoral Institution]`, etc. — bracketed placeholders throughout `index.html` and `teaching.html`
- The publication entries in `research.html` (title, authors, venue, summary, filename)
- The course list in `teaching.html`
- The student tables in `students.html`

## 2. Add your images and PDFs

- Put your headshot at `images/profile.jpg` and swap the placeholder block
  on `index.html` for an `<img>` tag — see `images/README.md` for the exact
  markup.
- Do the same for the research overview graphic and each publication
  thumbnail.
- Put your paper PDFs in `papers/` and make sure filenames match the
  `href` values on the download buttons in `research.html` (or edit the
  `href`s to match your filenames).
- Delete `images/README.md` and `papers/README.md` once you're done — they're
  just instructions, not part of the site.

## 3. Preview locally (optional)

Any static file server works. For example, with Python installed:

```
cd site
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## 4. Deploy on GitHub Pages

1. Create a new repository on GitHub. If you want the site at
   `https://yourusername.github.io`, name the repo exactly
   `yourusername.github.io`. Any other name works too — it'll be served at
   `https://yourusername.github.io/repo-name/`.
2. Push these files to the repository:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/yourusername/REPO_NAME.git
   git push -u origin main
   ```
3. On GitHub, go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch",
   pick the **main** branch and the **/ (root)** folder, then save.
5. GitHub will give you a URL (usually live within a minute or two) —
   that's your site.

Any time you push new commits to `main`, the live site updates automatically.

## Design notes

- Fonts (Fraunces, Inter, JetBrains Mono) load from Google Fonts via a
  `<link>` in each page's `<head>` — no local font files needed.
- Every photo/thumbnail across the site follows one motif: it's captioned
  like a figure in a paper ("Fig. 1 — ..."), tying the visual language to
  the fact that this is an academic's site.
- The publication list on `research.html` has client-side tag filtering
  (no page reload) via `js/main.js`.
- The site has no dark mode toggle by design — a single, considered "paper"
  palette keeps the figure/caption system consistent.
