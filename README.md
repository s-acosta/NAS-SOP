# NAS SOP - Goard Lab

This repository contains the Standard Operating Procedure (SOP) for the Network Attached Storage (NAS) system used in the Goard Lab.

## 🚀 Quick Start

This site is designed to be deployed on GitHub Pages. Follow these steps to get it running:

### 1. Create a New Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it something like `nas-sop` or `lab-nas-documentation`
3. Choose whether to make it public or private (note: GitHub Pages on private repos requires a paid account)
4. Don't initialize with README, .gitignore, or license (we have our own files)

### 2. Upload Files

You can either:

**Option A: Upload via Web Interface**
1. Click "uploading an existing file" on the empty repository page
2. Drag and drop `index.html` and `README.md`
3. Commit the files

**Option B: Use Git Command Line**
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
# Copy index.html and README.md to this directory
git add .
git commit -m "Initial commit: Add NAS SOP documentation"
git push origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"
7. Wait a few minutes for the site to build

### 4. Access Your Site

Your site will be available at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

## 📝 Updating the Documentation

To update the SOP:

1. Edit the `index.html` file
2. Commit and push your changes
3. GitHub Pages will automatically rebuild and deploy your site

## 🎨 Customization

The site uses embedded CSS for easy customization. You can modify:

- **Colors**: Look for the color values in the `<style>` section (e.g., `#667eea`, `#764ba2`)
- **Layout**: Adjust the `.container` max-width (currently 1000px)
- **Fonts**: Change the `font-family` in the `body` style

## 📋 Features

- ✅ Responsive design (mobile-friendly)
- ✅ Clean, modern interface
- ✅ Color-coded information boxes (info, warning, success)
- ✅ Step-by-step numbered workflow
- ✅ Table of contents with anchor links
- ✅ Print-friendly layout

## 🔧 Technical Details

- Single HTML file - no dependencies
- Pure CSS styling - no frameworks needed
- Lightweight and fast loading
- Compatible with all modern browsers

## 📞 Support

For questions about the NAS system or this documentation, contact Kevin.

---

**Original Document Written:** June 21, 2017 by KS  
**GitHub Pages Version Created:** November 2025
