# GitHub Pages Website

A clean, simple static website built with HTML and CSS, ready to deploy on GitHub Pages.

## Quick Start

1. **Edit your content**
   - `index.html` - Main website content
   - `styles.css` - All styling
   - `assets/` - Store images and other resources

2. **Test locally**
   - Use the "Start Local Server" task in VS Code (Ctrl+Shift+B or Cmd+Shift+B)
   - Visit http://localhost:8000

3. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

## Deploy to GitHub Pages

### For a repository site (username.github.io/repo-name):
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Build and deployment", select:
   - Source: **Deploy from a branch**
   - Branch: **main** (or your branch name)
   - Folder: **/ (root)**
4. Click **Save**
5. Your site will be live at: `https://username.github.io/repo-name`

### For a user/organization site (username.github.io):
1. Create a repository named `username.github.io`
   - Replace `username` with your actual GitHub username
2. Repeat steps 2-4 above
3. Your site will be live at: `https://username.github.io`

## File Structure

```
├── index.html           # Main website
├── styles.css          # Stylesheet
├── assets/             # Images and resources
├── README.md           # This file
└── .github/
    └── copilot-instructions.md
```

## Customization

- **Change the title**: Edit `<title>` in `index.html`
- **Update colors**: Modify CSS variables and colors in `styles.css`
- **Add new pages**: Create new `.html` files and link them in the navigation
- **Add images**: Place images in `assets/` folder and reference with `assets/image-name.jpg`

## Tips

- No build tools needed - just HTML and CSS
- Changes appear immediately when you push to GitHub (may take 1-2 minutes)
- You can use GitHub's built-in editor to make quick changes
- For more features, consider adding Jekyll or other static site generators

## Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [GitHub Pages Help](https://docs.github.com/en/pages)
- [HTML & CSS Reference](https://developer.mozilla.org/en-US/)
