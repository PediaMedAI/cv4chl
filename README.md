# AI4CHL Workshop Website

ICLR 2025 Workshop on AI for Children

**Live site:** https://pediamedai.github.io/cv4chl/

## 📁 Structure

```
cv4chl/
├── index.html              # Homepage (About)
├── callforpapers/          # Call for Papers page
├── organizers/             # Organizers page
├── schedule/               # Schedule page
└── assets/                 # All images, CSS, and JS files
```

## 🚀 Deployment

### Quick Start

```bash
cd cv4chl
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/pediamedai/cv4chl.git
git push -u origin main
```

Then enable GitHub Pages in repository settings:
- Settings > Pages
- Source: Branch `main`, Folder `/ (root)`

### Update Website

```bash
# After making changes
git add .
git commit -m "Update content"
git push
```

GitHub will automatically redeploy the site.

## ✏️ Editing

All pages are pure HTML files. Edit them with any text editor:

- Homepage: `index.html`
- Call for Papers: `callforpapers/index.html`
- Organizers: `organizers/index.html`
- Schedule: `schedule/index.html`
- Styles: `assets/css/main.css`

## 📝 Notes

- All links point to `https://pediamedai.github.io/cv4chl/`
- Navigation uses relative paths
- CSS loaded from CDN (requires internet)
- Images in `assets/` subdirectories

For detailed deployment instructions in Chinese, see `部署说明.md`.
