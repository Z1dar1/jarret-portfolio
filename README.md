# Jarret Dlugy Portfolio

Static, GitHub-Pages-ready mechanical engineering portfolio. No build tools, packages, or framework are required.

## Fastest way to edit

Use VS Code locally.

1. Clone/download this repository.
2. Open the folder in VS Code.
3. Edit `js/content.js` for nearly all text, project descriptions, skills, links, and metadata.
4. Replace/add images in `assets/images/` and update the matching image paths in `js/content.js`.
5. Open `index.html` with VS Code Live Server **or** run a small local server:

   ```bash
   python -m http.server 8000
   ```

6. Visit `http://localhost:8000`.
7. Commit and push changes to GitHub.

## Important files

- `index.html` — homepage structure. Rarely needs editing.
- `project.html` — reusable project case-study page. Rarely needs editing.
- `styles.css` — visual design and responsive layout.
- `js/content.js` — **edit this most often**.
- `js/main.js` — renders homepage data.
- `js/project.js` — renders the selected project case study.
- `assets/images/` — project visuals.
- `assets/Jarret_Dlugy_Resume.pdf` — résumé linked throughout the site.

## Add a new project

In `js/content.js`, duplicate one object inside `projects: [...]` and change:

- `id`
- `label`
- `title`
- descriptions
- hero image
- tags
- facts
- case-study sections
- gallery images

The homepage card and full project page are generated automatically.

## Publish with GitHub Pages

For the working repository, go to:

`Settings → Pages → Build and deployment → Deploy from a branch → main / root`

If this repository is eventually moved to Jarret's account and renamed to `HISUSERNAME.github.io`, the public URL becomes:

`https://HISUSERNAME.github.io`

## Before final launch

- Confirm Jarret is comfortable publishing the current email address.
- Confirm no internship/project image or detail is confidential/proprietary.
- Check résumé filename and content.
- Test every page on a phone.
- Add any Lexington Medical visuals only if they are approved for public release.
