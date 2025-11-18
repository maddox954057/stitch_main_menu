# Quick Guide: Upload Latest Updates to GitHub

## If you already have a GitHub repository:

### Option 1: Using GitHub Web Interface (Easiest - No Git Required)

1. Go to your GitHub repository page (e.g., `https://github.com/YOUR_USERNAME/REPOSITORY_NAME`)
2. Click on `index.html` to view it
3. Click the **pencil icon** (✏️) to edit the file
4. **Delete all the existing content** in the editor
5. Open your local `index.html` file from `C:\Users\maddo\.cursor\stitch_main_menu\index.html`
6. **Copy all content** (Ctrl+A, Ctrl+C)
7. **Paste it** into the GitHub editor (Ctrl+V)
8. Scroll down and click **"Commit changes"**
9. Add a commit message like: "Update: Quest system, load game fix, reset button, and more"
10. Click **"Commit changes"**

### Option 2: Using Git Command Line (If Git is Installed)

Open PowerShell or Command Prompt in the `stitch_main_menu` folder and run:

```powershell
cd C:\Users\maddo\.cursor\stitch_main_menu
git add index.html
git commit -m "Update: Quest system with claim button, load game fix, reset button in inventory, support tower unlock change, admin mode gold fix"
git push origin main
```

## If you DON'T have a GitHub repository yet:

Follow the instructions in `GITHUB_DEPLOY.md` to create a new repository first.

---

## Recent Updates Included:

✅ Quest system with claim button (no auto-reward)
✅ Quest progress tracking fixed
✅ Load game function fixed (wave resets to 1, zombies spawn correctly)
✅ Reset button added to inventory screen
✅ Support tower unlock changed to Desert Oasis
✅ Admin mode no longer gives unlimited coins
✅ Whispering Woods gold text color fixed (white for visibility)
✅ Exit button stops game loop properly

---

**Your game file location:**
`C:\Users\maddo\.cursor\stitch_main_menu\index.html`

