# Jianhua He — Personal Academic Website (Version 3)

This version is designed as a general personal academic website rather than an IET-specific evidence page.

## Files

- `index.html` — all visible text, headings, lists, publications and links
- `style.css` — colours, spacing, typography and responsive layout
- `README.md` — editing and publishing notes

No JavaScript, framework, database, build system or external font is used.

## Which file should I edit?

### For content changes: edit `index.html`

Use this file to change your biography, research topics, publications, projects, conference roles, awards, supervision numbers, citation counts and external links. You will probably make 95% of future changes only in `index.html`.

### For appearance changes: edit `style.css`

Use this file only if you want to change font size, page width, spacing, colours, line thickness or the mobile layout. If you are happy with the present visual design, leave `style.css` unchanged.

## Recommended editing software

**Visual Studio Code (VS Code)** is the easiest choice.

1. Open VS Code.
2. Choose **File → Open Folder** and select this website folder.
3. Click `index.html`.
4. Find the section you want to edit.
5. Change the text between the HTML tags.
6. Save with `Ctrl+S` on Windows or `Cmd+S` on Mac.
7. Open `index.html` in Chrome, Edge or Safari to preview it.

Notepad++ also works, but VS Code makes the HTML structure easier to read.

## How to find each section

Search inside `index.html` for:

- `<section id="about">`
- `<section id="research">`
- `<section id="selected-publications">`
- `<section id="projects-funding">`
- `<section id="innovation-impact">`
- `<section id="leadership-service">`
- `<section id="awards-recognition">`
- `<section id="supervision">`
- `<section id="links">`

The navigation menu points to exactly these sections.

## Final review notes

1. The site is intentionally concise and does not repeat the full IET Creativity or Innovation statements.
2. The Top 2% Scientists link supplied by the applicant is included directly.
3. The Google Scholar link is the one linked from the University of Essex profile.
4. IEEE GLOBECOM 2028 is worded conservatively because the nomination remains subject to final conference approval.
5. Ping An / PICC remains omitted until the exact customer identity is confirmed.
6. Commercial deployment figures are retained because they were supplied and confirmed by the applicant; add public or company-authorised supporting evidence if available.
7. Conference names are written in full where identifiable. If an official workshop title differs, edit only that line in `index.html`.
8. Citation counts should be refreshed shortly before formal use.

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` and `style.css`.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**.
5. Choose `main` and `/ (root)`.
6. Save.

For a personal site, naming the repository `<your-GitHub-username>.github.io` gives the cleanest address:

`https://<your-GitHub-username>.github.io/`
