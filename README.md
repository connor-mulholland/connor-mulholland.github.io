# Connor Mulholland — Academic Website

A static academic website designed for GitHub Pages.

## Publish in about five minutes

1. Create a public GitHub repository named exactly `YOUR-USERNAME.github.io`.
2. Upload **the contents of this folder** to the repository root. Do not upload the enclosing folder as an extra directory.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Visit `https://YOUR-USERNAME.github.io` after GitHub finishes deployment.

## Replace the photo placeholder

The homepage currently shows a tasteful `CM` placeholder. To use a professional headshot:

1. Add a square or portrait image to `images/profile.jpg`.
2. In `index.html`, replace:

```html
<div class="portrait-placeholder" aria-label="Photo placeholder">CM</div>
```

with:

```html
<img class="portrait-placeholder" src="images/profile.jpg" alt="Connor Mulholland">
```

The existing CSS will crop it to the correct shape. You may add `object-fit: cover;` to `.portrait-placeholder` if needed.

## Add papers

Place PDFs in the `files` folder, then replace a “Request paper” link with, for example:

```html
<a href="files/farmers-facing-risk.pdf">Download paper</a>
```

Use short, stable lowercase filenames without spaces.

## Update the CV

Replace `files/Connor_Mulholland_CV.pdf` with the new PDF while preserving that filename. All CV links will update automatically.

## Optional edits before publishing

- Add your Google Scholar link once the profile is ready.
- Add a professional headshot.
- Upload public working-paper PDFs.
- Add teaching evaluations or syllabi only when they are polished and intended for public distribution.

## Included current materials

- `images/connor-mulholland.jpg`: current professional headshot used on the homepage.
- `files/Connor_Mulholland_CV.pdf`: current CV supplied in July 2026.

To update either later, replace the file while keeping the same filename.
