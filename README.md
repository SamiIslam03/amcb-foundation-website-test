# AMCB Foundation Bangladesh Website

This is the official website for the AMCB Foundation Bangladesh, an organization making a difference in rural communities.

## Deployment

This website is automatically deployed to GitHub Pages using GitHub Actions.

### Setup Instructions

1. **Enable GitHub Pages** in your repository settings:
   - Go to Settings > Pages
   - Under "Build and deployment", select "GitHub Actions" as the source

2. **Automatic Deployment**: The website will automatically deploy when changes are pushed to the `main` branch.

3. **Manual Deployment**: You can also trigger a manual deployment from the Actions tab by running the "Deploy to GitHub Pages" workflow.

## Local Development

This is a static HTML website. To view it locally:

1. Open `index.html` in your web browser
2. Or use a simple HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit http://localhost:8000

## Structure

- `index.html` - Main website file
- `images/` - Website images and assets
- `cv/` - CV and resume files
- `.github/workflows/deploy.yml` - GitHub Actions deployment workflow
