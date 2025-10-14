# 🚀 GitHub Pages Deployment Guide

This guide will walk you through setting up GitHub Pages for your Career History portfolio.

---

## 📋 Prerequisites

- [x] GitHub account ([ajwebste1981](https://github.com/ajwebste1981))
- [x] Repository created: `Career_History`
- [x] Files ready to deploy:
  - `index.md` (landing page)
  - `Andrew_Webster_Complete_Career_History.md` (complete documentation)
  - `_config.yml` (Jekyll configuration)
  - `README.md` (repository documentation)

---

## 🎯 Step-by-Step Deployment

### Step 1: Upload Files to GitHub

1. **Navigate to your repository:**
   - Go to [https://github.com/ajwebste1981/Career_History](https://github.com/ajwebste1981/Career_History)

2. **Upload the files:**
   
   **Option A: Using GitHub Web Interface**
   - Click **"Add file"** → **"Upload files"**
   - Drag and drop these files:
     - `index.md`
     - `Andrew_Webster_Complete_Career_History.md`
     - `_config.yml`
     - `README.md`
     - `DEPLOYMENT_GUIDE.md` (this file)
   - Add commit message: `Initial portfolio setup`
   - Click **"Commit changes"**

   **Option B: Using Git Command Line**
   ```bash
   # Clone the repository
   git clone https://github.com/ajwebste1981/Career_History.git
   cd Career_History

   # Copy all files to the repository directory
   # (Copy index.md, Andrew_Webster_Complete_Career_History.md, _config.yml, README.md, DEPLOYMENT_GUIDE.md)

   # Add all files
   git add .

   # Commit
   git commit -m "Initial portfolio setup"

   # Push to GitHub
   git push origin main
   ```

---

### Step 2: Enable GitHub Pages

1. **Go to Repository Settings:**
   - Navigate to your repository: [https://github.com/ajwebste1981/Career_History](https://github.com/ajwebste1981/Career_History)
   - Click **"Settings"** tab (top right)

2. **Navigate to Pages:**
   - In the left sidebar, scroll down and click **"Pages"**

3. **Configure GitHub Pages:**
   - **Source:** Select **"Deploy from a branch"**
   - **Branch:** Select **"main"** (or **"master"** if that's your default branch)
   - **Folder:** Select **"/ (root)"**
   - Click **"Save"**

4. **Wait for deployment:**
   - GitHub will start building your site automatically
   - This usually takes 1-3 minutes
   - You'll see a message: *"Your site is live at https://ajwebste1981.github.io/Career_History/"*

---

### Step 3: Verify Your Site is Live

1. **Check the deployment:**
   - Go to **"Actions"** tab in your repository
   - You should see a workflow called **"pages build and deployment"**
   - Wait for the green checkmark ✅

2. **Visit your live site:**
   - Open: [https://ajwebste1981.github.io/Career_History/](https://ajwebste1981.github.io/Career_History/)
   - You should see your portfolio landing page!

3. **Test navigation:**
   - Click on **"Complete Career History"** link
   - Verify all internal links work
   - Check that badges and images display correctly

---

## 🎨 Optional: Choose a Theme

GitHub Pages supports several built-in themes. To change the theme:

1. **Go to Repository Settings → Pages**

2. **Click "Choose a theme" or "Change theme"**

3. **Select a theme:**
   - **Minima** (Default) - Clean, minimal design ✅ Recommended
   - **Slate** - Dark theme with sidebar
   - **Cayman** - Blue gradient header
   - **Architect** - Professional with sidebar
   - **Tactile** - Clean with top navigation

4. **Preview and select your preferred theme**

5. **Your `_config.yml` will automatically update**

---

## 🔧 Customization Options

### Update Site Title or Description

Edit `_config.yml`:

```yaml
title: Andrew J Webster - Game Production Portfolio
description: Your custom description here
```

### Add Custom Domain (Optional)

If you own a custom domain:

1. **Go to Settings → Pages**
2. **Under "Custom domain", enter your domain** (e.g., `andrewwebster.com`)
3. **Follow GitHub's instructions to configure DNS**

---

## 📝 Making Updates

### To Update Content:

1. **Edit files in your repository:**
   - Use GitHub's web editor (click file → pencil icon)
   - Or edit locally and push changes via Git

2. **Commit your changes:**
   - Add a descriptive commit message
   - Click "Commit changes"

3. **GitHub Pages will automatically rebuild:**
   - Usually takes 1-3 minutes
   - Check the "Actions" tab to monitor progress

---

## 🐛 Troubleshooting

### Site Not Displaying?

1. **Check Pages settings:**
   - Settings → Pages
   - Ensure "Source" is set to "main" branch, "/ (root)" folder

2. **Check Actions tab:**
   - Look for red X ❌ indicating build errors
   - Click on the failed action to see error details

3. **Common issues:**
   - **404 Error:** Wait 2-3 minutes for initial deployment
   - **Styling broken:** Clear browser cache (Ctrl+F5)
   - **Links not working:** Ensure `baseurl` in `_config.yml` is set to `/Career_History`

### Links Not Working?

Ensure your `_config.yml` has the correct `baseurl`:

```yaml
baseurl: "/Career_History"
url: "https://ajwebste1981.github.io"
```

### Images or Badges Not Showing?

- Check that image URLs are correct
- Shields.io badges require internet connection
- GitHub caches images; may take a few minutes to update

---

## 🔒 Privacy Settings

### Make Repository Public (Required for Free GitHub Pages)

If your repository is private:

1. **Go to Settings → General**
2. **Scroll to "Danger Zone"**
3. **Click "Change visibility"**
4. **Select "Make public"**

Note: GitHub Pages requires public repositories for free accounts.

---

## ✅ Success Checklist

After deployment, verify:

- [ ] Site loads at `https://ajwebste1981.github.io/Career_History/`
- [ ] Landing page displays correctly
- [ ] "Complete Career History" link works
- [ ] Table of Contents links navigate correctly
- [ ] Badges display properly
- [ ] External links (LinkedIn, MobyGames, Webster AI Chef) work
- [ ] Site is mobile-responsive

---

## 📊 Analytics (Optional)

To track visitors to your portfolio:

1. **Sign up for Google Analytics** (free)
2. **Get your tracking ID** (e.g., `G-XXXXXXXXXX`)
3. **Add to `_config.yml`:**
   ```yaml
   google_analytics: G-XXXXXXXXXX
   ```

---

## 🚀 Next Steps

Once your site is live:

1. **Share your portfolio:**
   - Add to LinkedIn profile
   - Include in email signatures
   - Share in job applications

2. **Update regularly:**
   - Add new accomplishments
   - Update contact information
   - Refresh technical projects

3. **Monitor performance:**
   - Use Google Analytics (if added)
   - Check for broken links periodically
   - Update content quarterly

---

## 📞 Need Help?

If you encounter issues:

1. **Check GitHub Pages documentation:**
   - [https://docs.github.com/en/pages](https://docs.github.com/en/pages)

2. **Check Jekyll documentation:**
   - [https://jekyllrb.com/docs/](https://jekyllrb.com/docs/)

3. **GitHub Community:**
   - [https://github.community/](https://github.community/)

---

## 🎉 Congratulations!

Your professional portfolio is now live and ready to share with the world!

**Your Live Site:** [https://ajwebste1981.github.io/Career_History/](https://ajwebste1981.github.io/Career_History/)

---

<div align="center">

**Built with ❤️ for your career success**

*Last Updated: October 2024*

</div>

