# Project: What is up with AI? Blog

## Overview
Hugo-based blog for exploring AI topics, deployed via GitHub Pages.

## Setup Complete
- ✅ Hugo site initialized
- ✅ PaperMod theme installed
- ✅ Basic configuration (hugo.toml)
- ✅ GitHub Actions workflow for deployment
- ✅ Project structure created

## Next Steps

### Before First Deploy
1. Create GitHub repository
2. Update `baseURL` in hugo.toml with your GitHub username
3. Push code to GitHub
4. Enable GitHub Pages (Settings → Pages → Source: GitHub Actions)

### Content Creation
1. Write your first real blog post:
   ```bash
   hugo new posts/my-first-post.md
   ```
2. Edit the markdown file in `content/posts/`
3. Set `draft = false` when ready to publish

### Customization Ideas
- Update site title/description in hugo.toml
- Customize theme colors/fonts
- Add social media links
- Set up comments system
- Add analytics

### Useful Commands
- `hugo server -D` - Local development with drafts
- `hugo new posts/title.md` - Create new post
- `git push origin main` - Deploy to GitHub Pages

## Technical Notes
- Hugo version: 0.136.4
- Theme: PaperMod
- Deployment: GitHub Actions → GitHub Pages
- Branch: main triggers deployment