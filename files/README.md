# myungeun-eom.github.io

Personal academic website. Plain HTML + CSS, served by GitHub Pages — no build step,
no Jekyll, no dependencies. Editing `index.html` and pushing is the whole workflow.

## Files to add before publishing

| File | Where to get it |
|---|---|
| `photo.jpg` | https://sites.gatech.edu/myungeun-eom/files/2022/10/myungeun_photo_cropped-1-1024x1024.jpg |
| `files/CV_MyungeunEom.pdf` | https://sites.gatech.edu/myungeun-eom/files/2026/01/CV_MyungeunEom.pdf |
| `files/Dynamic_matching_poster.pdf` | https://sites.gatech.edu/myungeun-eom/files/2025/03/Dynamic_matching_poster.pdf |

Also replace `YOUR-EMAIL@auburn.edu` in `index.html`.

## Editing

- Add a paper: copy an existing `<li>` inside `<ol class="pubs">` and change the text.
- Add a talk: copy an `<li>` inside the `#talks` section.
- Add a whole section: copy a `<section>` block, give it a new `id`, and add a matching
  `<li><a href="#newid">Name</a></li>` to the nav.
- Colors, fonts, and spacing all live at the top of `style.css` under `:root`.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and
visit http://localhost:8000.

## Deploy

Push to `main`. GitHub Pages publishes within a minute or two.
