# 🚀 GitHub Setup Guide

## Quick Setup Instructions

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com)
2. Click the **+** icon in the top right
3. Select **New repository**
4. Fill in:
   - **Repository name:** `nonprofit-mission-generator` (or your preferred name)
   - **Description:** "Interactive mission statement generator for nonprofit leaders"
   - **Public** or **Private** (Public recommended for GitHub Pages)
   - ❌ Don't initialize with README (we already have one)
5. Click **Create repository**

### Step 2: Push Your Code

GitHub will show you commands. Use these instead:

```bash
cd /home/claude/nonprofit-mission-generator
git remote add origin https://github.com/YOUR-USERNAME/nonprofit-mission-generator.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username.

### Step 3: Enable GitHub Pages (Optional but Recommended)

This hosts your calculator for free!

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes
7. Your site will be live at: `https://YOUR-USERNAME.github.io/nonprofit-mission-generator/`

### Step 4: Use in Squarespace

**Option A: Direct Embed (Code Block)**
1. Open `index.html` from your repository
2. Click the **Raw** button
3. Copy all the code
4. In Squarespace, add a **Code Block**
5. Paste the HTML code
6. Save and publish

**Option B: iFrame Embed (if using GitHub Pages)**
1. Add an **Embed Block** in Squarespace
2. Use this code:
```html
<iframe 
  src="https://YOUR-USERNAME.github.io/nonprofit-mission-generator/" 
  width="100%" 
  height="1200px" 
  frameborder="0"
  style="border: none;">
</iframe>
```

---

## Updating Your Calculator

When you make changes:

```bash
cd /home/claude/nonprofit-mission-generator
# Make your edits to index.html
git add .
git commit -m "Description of your changes"
git push
```

If using GitHub Pages, changes appear in 1-2 minutes.
If using direct embed, you'll need to update the code in Squarespace.

---

## Troubleshooting

**Can't push to GitHub?**
- Make sure you've created the repository first
- Verify you replaced `YOUR-USERNAME` with your actual username
- You may need to authenticate (use personal access token, not password)

**GitHub Pages not working?**
- Make sure the repository is **Public**
- Wait 2-5 minutes after enabling Pages
- Check that the branch is set to `main` and folder to `/`

**Changes not showing?**
- Hard refresh your browser (Ctrl+F5 or Cmd+Shift+R)
- Clear your browser cache
- Wait a few minutes for GitHub Pages to rebuild

---

## Next Steps

✅ Your repository is ready to push!
✅ Files included:
   - `index.html` - The calculator
   - `README.md` - Documentation
   - `LICENSE` - MIT License
   - `SQUARESPACE_INSTRUCTIONS.md` - Detailed Squarespace guide
   - `.gitignore` - Git configuration

**Ready to push? Follow Step 2 above!**
