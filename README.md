# Jarret Dlugy Portfolio

This is your mechanical engineering portfolio website.

It is built to be simple to maintain and is hosted through GitHub Pages, so you do not need to pay for web hosting or use any special software to keep it updated.

## How to make changes

The easiest way to update the site is with VS Code.

1. Open the portfolio folder in VS Code.
2. Most of the content you will ever need to change is in:

   `js/content.js`

3. Use that file to update:
   - project descriptions
   - experience
   - skills
   - links
   - About section
   - graduation information
   - project images and captions

4. Put new photos or engineering images inside:

   `assets/images/`

5. Update the matching image filename in `js/content.js`.

6. To preview the website before publishing anything, open `index.html` using the VS Code Live Server extension.

7. When you are happy with the changes, commit and push them to GitHub.

GitHub Pages will automatically update the public website after the changes are pushed.

## Important files

### `js/content.js`
This is the main file you should edit.

Most of the text and project information on the website lives here.

### `assets/images/`
This is where the project photos, CAD images, drawings, and personal photos are stored.

### `assets/Jarret_Dlugy_Resume.pdf`
This is the resume linked throughout the website.

If you update your resume in the future, replace this PDF with the new version using the same filename.

### `styles.css`
This controls how the website looks.

You probably will not need to edit this unless you want to change the design, colors, spacing, fonts, or layout.

### `index.html`
This controls the basic structure of the homepage.

You should rarely need to change this.

### `project.html`
This is the reusable page used for each engineering project.

You should rarely need to change this either.

## Adding a new project

Adding another project is mostly done inside:

`js/content.js`

Find the `projects` section and duplicate one of the existing project entries.

Then update:

- project ID
- project title
- year or organization
- short description
- main image
- skills/tags
- project facts
- case study sections
- gallery images

The homepage project card and full project page are created automatically from that information.

Put any new images for the project inside:

`assets/images/`

## Updating the resume

When you have a new resume:

1. Export it as a PDF.
2. Name it:

   `Jarret_Dlugy_Resume.pdf`

3. Replace the existing file inside the `assets` folder.
4. Commit and push the change.

All of the Resume buttons on the website will automatically use the new version.

## Your public website

While the website is still on Mehdi's GitHub account, it can be hosted as a GitHub Pages project site.

Once the repository is moved to your GitHub account, rename the repository to:

`YOURUSERNAME.github.io`

Your website will then be available at:

`https://YOURUSERNAME.github.io`

Anyone can open this link without having a GitHub account.

You can put the link on your:

- resume
- LinkedIn
- email signature
- job applications

## Publishing changes

If GitHub Pages ever needs to be enabled again:

Go to:

`Settings > Pages > Build and deployment`

Choose:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`

Then save.

## Before publishing new work

Before adding anything from an internship, employer, lab, or team project, make sure it is okay to share publicly.

Do not upload confidential drawings, internal documents, proprietary designs, private test data, or anything covered by an NDA.

For Lexington Medical in particular, only add images or technical details that you know are approved for public use.

## Final note

The website is intentionally built to be easy to maintain.

For most updates, you should only need to change:

`js/content.js`

and occasionally add or replace files inside:

`assets/images/`

You should not need to rebuild the website every time you add a new project.