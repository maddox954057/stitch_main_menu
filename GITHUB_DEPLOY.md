# Deploy to GitHub Pages

## Step 1: Create a GitHub Repository

1. Go to https://github.com and sign in (or create an account)
2. Click the "+" icon in the top right → "New repository"
3. Name it (e.g., `tower-defense-game`)
4. Make it **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

## Step 2: Upload Files via GitHub Web Interface

1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop the `index.html` file from the `stitch_main_menu` folder
3. Click **"Commit changes"** at the bottom

## Step 3: Enable GitHub Pages

1. Go to your repository's **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select:
   - Branch: **main** (or **master**)
   - Folder: **/ (root)**
4. Click **Save**
5. Wait a few minutes for GitHub to build your site

## Step 4: Access Your Game

Your game will be available at:
```
https://YOUR_USERNAME.github.io/REPOSITORY_NAME/
```

For example: `https://johndoe.github.io/tower-defense-game/`

---

## Alternative: Using Git Command Line

If you have Git installed, you can use these commands:

```bash
cd stitch_main_menu
git init
git add index.html README.md
git commit -m "Initial commit: Tower Defense Game"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
git push -u origin main
```

Then follow Step 3 above to enable GitHub Pages.

