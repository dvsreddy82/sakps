# GitHub Pages Setup Guide (Jekyll)

## Quick Start

Your Jekyll website is ready to be published! GitHub Pages will automatically build and deploy your Jekyll site.

### Step 1: Push Your Code (Already Done!)

Your code has been pushed to: `https://github.com/dvsreddy82/sakps`

### Step 2: Enable GitHub Pages

1. Go to your repository: https://github.com/dvsreddy82/sakps/settings/pages
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**

### Step 3: Access Your Website

- Your website will be live at: `https://dvsreddy82.github.io/sakps/`
- GitHub Pages will automatically detect Jekyll and build your site
- It may take 1-2 minutes for the site to be available
- GitHub will show you the URL once it's ready

### Step 4: Verify Build Status

- Go to the **Actions** tab in your repository
- You'll see the Jekyll build process
- Green checkmark = site built successfully

## Local Development

To test your Jekyll site locally:

```bash
# Install dependencies
bundle install

# Run Jekyll server
bundle exec jekyll serve

# Visit http://localhost:4000/sakps/
```

## Customization

### Update Site Information
Edit `_config.yml` to change:
- Site title and description
- Services and features
- Location information
- Google Maps URLs

### Update Content
- Edit `_includes/` files for sections
- Edit `assets/css/styles.css` for styling
- Edit `assets/js/script.js` for interactivity

## Troubleshooting

- **Site not loading?** 
  - Check the Actions tab for build errors
  - Wait 1-2 minutes after enabling Pages
  - Verify `_config.yml` has correct `baseurl: "/sakps"`

- **Changes not showing?**
  - Make sure you've pushed to the `main` branch
  - Check Actions tab for build status
  - Clear browser cache

- **404 error?**
  - Verify `baseurl` in `_config.yml` matches your repository name
  - Check that `index.html` exists in root

- **Build errors?**
  - Check Actions tab for error messages
  - Verify YAML syntax in `_config.yml`
  - Ensure all includes are in `_includes/` folder

## Updating Your Website

To make changes:

```bash
# Make your changes to files
git add .
git commit -m "Update website content"
git push origin main
```

GitHub Pages will automatically rebuild your site within 1-2 minutes!

## Jekyll Benefits

✅ Automatic site generation  
✅ Easy content management via `_config.yml`  
✅ Modular includes for reusable components  
✅ GitHub Pages native support  
✅ Fast builds and deployments  
