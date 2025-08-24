# What is up with AI?

A Hugo blog exploring the world of artificial intelligence.

## Quick Start

### Local Development
```bash
hugo server -D
```
Visit http://localhost:1313

### Create New Post
```bash
hugo new posts/your-post-title.md
```

### Build Site
```bash
hugo
```

## Deployment

This site is configured to deploy automatically to GitHub Pages when you push to the `main` branch.

### Setup Steps:
1. Create a GitHub repository
2. Push this code to the repository
3. Go to Settings → Pages in your repo
4. Set Source to "GitHub Actions"
5. Update `baseURL` in `hugo.toml` to match your GitHub Pages URL

## Theme

Using [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Structure

- `content/` - Your blog posts and pages
- `themes/` - Hugo themes (PaperMod)
- `public/` - Generated site (gitignored)
- `.github/workflows/` - GitHub Actions for deployment