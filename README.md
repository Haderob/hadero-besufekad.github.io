# Hadero Besufekad Tadele Academic Website

This is a Jekyll-based personal academic website designed for GitHub Pages.

## Structure

- `_config.yml`: site metadata, social links, and navigation.
- `_layouts/default.html`: shared page layout.
- `assets/css/style.scss`: custom visual design.
- `index.md`, `about.md`, `research.md`, `publications.md`, `projects.md`, `cv.md`, `contact.md`: site pages.
- `assets/files/CV_Besufekad_PhD.pdf`: downloadable CV.
- `assets/img/profile.png`: profile image.

## Run Locally

1. Install Ruby and Bundler if they are not already installed.
2. From this folder, install the GitHub Pages gems:

```bash
bundle install
```

3. Start the local server:

```bash
bundle exec jekyll serve
```

4. Open:

```text
http://localhost:4000
```

If GitHub Pages reports a different repository URL, update `url` in `_config.yml`.

## Deploy to GitHub Pages

1. Create a public repository named `hadero-besufekad.github.io`.
2. Upload or push the contents of this folder to the repository root.
3. In GitHub, open `Settings` -> `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.
6. Save and wait for GitHub Pages to build the site.

The site should be available at:

```text
https://hadero-besufekad.github.io
```

## Maintenance Notes

- Edit Markdown pages to update content.
- Replace `assets/files/CV_Besufekad_PhD.pdf` when the CV changes.
- Replace `assets/img/profile.png` to update the profile photo.
- Confirm and add a Google Scholar URL in `_config.yml` and `contact.md` when available.
