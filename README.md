# Besufekad T. Hadero — Academic Personal Website

This is a Jekyll-based academic personal website hosted on GitHub Pages.

## Quick Setup

### 1. Create Your GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository named **`hadero-besufekad.github.io`**
   - Make it **public**
   - Do not initialize with a README (you already have these files)

### 2. Upload to GitHub

Option A: Using Git
```bash
git init
git add .
git commit -m "Initial website commit"
git branch -M main
git remote add origin https://github.com/hadero-besufekad/hadero-besufekad.github.io.git
git push -u origin main
```

Option B: Drag and drop
1. Zip all files in this folder
2. Go to your repository on GitHub
3. Click "Add file" → "Upload files"
4. Drag and drop all files
5. Commit

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Build and deployment", select **Source: Deploy from a branch**
4. Choose **Branch: main**, folder **/(root)**
5. Click **Save**

Your site will be live at **`https://hadero-besufekad.github.io`** within a few minutes!

## Updating Your Site

To update, simply edit the `.md` files and push changes to GitHub. GitHub Pages will automatically rebuild.

## Customization

- Edit `_config.yml` to update social links or navigation
- Add new pages by creating `.md` files and adding them to the navigation list in `_config.yml`
- Edit `assets/css/style.scss` to change colors or fonts

## Need Help?

- [Jekyll documentation](https://jekyllrb.com/docs/)
- [GitHub Pages documentation](https://docs.github.com/en/pages)
- [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)
