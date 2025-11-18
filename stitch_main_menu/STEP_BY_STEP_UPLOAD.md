# Step-by-Step: Upload Your Game to GitHub

## 🎯 Goal: Get your Tower Defense game online!

---

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to **https://github.com**
2. Click **"Sign up"** (top right)
3. Create your account (it's free!)
4. Verify your email

---

## Step 2: Create a New Repository

1. After logging in, click the **"+"** icon in the top right corner
2. Click **"New repository"**
3. Fill in:
   - **Repository name**: `tower-defense-game` (or any name you like)
   - **Description**: "Tower Defense Game - HTML5 Game"
   - **Visibility**: Select **Public** (required for free hosting)
   - **DO NOT** check "Add a README file"
   - **DO NOT** check "Add .gitignore"
   - **DO NOT** check "Choose a license"
4. Click **"Create repository"** (green button)

---

## Step 3: Upload Your Game File

1. On your new repository page, you'll see a page that says "Quick setup"
2. Look for the section that says **"uploading an existing file"** (it's a link, usually in gray text)
3. Click **"uploading an existing file"**
4. You'll see a file upload area
5. **Open File Explorer** on your computer
6. Navigate to: `C:\Users\maddo\.cursor\stitch_main_menu`
7. **Drag and drop** the `index.html` file into the GitHub upload area
   - OR click "choose your files" and browse to select `index.html`
8. Scroll down to the bottom of the page
9. In the "Commit changes" section:
   - **Commit message**: Type "Initial upload: Tower Defense Game"
   - Leave "Add a commit description" empty (optional)
10. Click the green **"Commit changes"** button

---

## Step 4: Enable GitHub Pages (Make Your Game Live!)

1. After uploading, go to your repository page
2. Click the **"Settings"** tab (top menu)
3. Scroll down the left sidebar and click **"Pages"**
4. Under **"Source"**:
   - Select **"Deploy from a branch"**
   - **Branch**: Select `main` (or `master` if that's what you have)
   - **Folder**: Select `/ (root)`
5. Click **"Save"** button
6. Wait 1-2 minutes for GitHub to build your site

---

## Step 5: Access Your Live Game!

1. After saving, GitHub will show you a link like:
   ```
   https://YOUR_USERNAME.github.io/tower-defense-game/
   ```
2. Click the link or copy it
3. Your game is now live! 🎉
4. Share this link with anyone!

---

## 🔄 To Update Your Game Later:

When you make changes to your game:

1. Go to your repository on GitHub
2. Click on `index.html` file
3. Click the **pencil icon** (✏️) to edit
4. **Delete all the old content** (Ctrl+A, Delete)
5. Open your local file: `C:\Users\maddo\.cursor\stitch_main_menu\index.html`
6. **Copy all content** (Ctrl+A, Ctrl+C)
7. **Paste into GitHub editor** (Ctrl+V)
8. Scroll down, add commit message: "Update: [describe your changes]"
9. Click **"Commit changes"**
10. Wait 1-2 minutes for GitHub Pages to update

---

## ❓ Troubleshooting

**Problem**: "Page not found" after enabling Pages
- **Solution**: Wait 2-3 minutes, then refresh. GitHub needs time to build.

**Problem**: Game doesn't work when I open the link
- **Solution**: Make sure you uploaded `index.html` (not a folder), and it's in the root of your repository.

**Problem**: Can't find "uploading an existing file" link
- **Solution**: Look for a gray text link that says "uploading an existing file" or "upload files" near the top of your empty repository page.

---

## 📝 Quick Checklist

- [ ] Created GitHub account
- [ ] Created new repository (Public)
- [ ] Uploaded `index.html` file
- [ ] Enabled GitHub Pages in Settings
- [ ] Got your live game URL
- [ ] Tested the game link

---

**Your game file location:**
`C:\Users\maddo\.cursor\stitch_main_menu\index.html`

**Need more help?** Check `GITHUB_DEPLOY.md` for more detailed instructions.

