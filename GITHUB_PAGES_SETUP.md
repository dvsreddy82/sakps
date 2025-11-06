# GitHub Pages Setup Guide

## Quick Start

Your website is ready to be published! Follow these steps:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it (e.g., `sri-ankalamma-kennels` or `sakps`)
5. **Do NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

### Step 2: Push Your Code to GitHub

Run these commands in your terminal (replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual values):

```bash
cd /Users/ravikirank/projects/sakps

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push your code
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 4: Access Your Website

- Your website will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`
- It may take 1-2 minutes for the site to be available
- GitHub will show you the URL once it's ready

### Step 5: Custom Domain (Optional)

If you have a custom domain:
1. In the Pages settings, add your domain
2. Update your DNS records as instructed by GitHub

## Troubleshooting

- **Site not loading?** Wait a few minutes and refresh
- **Changes not showing?** Make sure you've pushed to the `main` branch
- **404 error?** Check that `index.html` is in the root directory

## Updating Your Website

To make changes:

```bash
# Make your changes to files
git add .
git commit -m "Update website content"
git push origin main
```

Changes will be live within 1-2 minutes!

