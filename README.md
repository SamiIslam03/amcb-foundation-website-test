# AMCB Foundation Bangladesh Website

This repository contains the website for AMCB Foundation Bangladesh, a non-profit organization dedicated to improving lives in rural Bangladesh through medical care, disaster relief, and community development.

## 🌐 Website URL Configuration

### Current Issue
The website is currently being served from `http://samiislam.me/amcb-test/` but should be accessible via GitHub Pages default URL.

### Solution Steps

#### 1. Remove Custom Domain (Required)
To use the default GitHub Pages URL, you need to remove the custom domain configuration:

1. Go to **Repository Settings** → **Pages**
2. Under **Custom domain**, remove `samiislam.me` or any custom domain
3. Click **Save**

#### 2. Choose Correct Repository Name
Currently, the repository is named `amcb-foundation-website-test`. Based on this:

**Option A: Keep Current Name**
- GitHub Pages URL will be: `https://samiislam03.github.io/amcb-foundation-website-test/`

**Option B: Rename to Match Expected Path**
- If you want the URL to be `https://samiislam03.github.io/amcb-test/`:
  1. Go to **Repository Settings**
  2. Rename repository from `amcb-foundation-website-test` to `amcb-test`
  3. GitHub Pages URL will automatically become: `https://samiislam03.github.io/amcb-test/`

#### 3. Enable HTTPS (Recommended)
After removing custom domain:
1. Go to **Repository Settings** → **Pages**
2. Check **Enforce HTTPS** option
3. This will ensure the site uses `https://` instead of `http://`

### GitHub Pages Configuration
- **Source**: Deploy from main branch
- **Path**: / (root)
- **No CNAME file needed** (for default GitHub Pages URL)

## 📁 Repository Structure
```
.
├── index.html          # Main website file
├── images/            # Website images and assets
├── cv/                # CV-related files
└── README.md          # This file
```

## 🚀 Deployment
The website is automatically deployed via GitHub Pages when changes are pushed to the main branch.

## 📝 Development
This is a static HTML website with inline CSS and JavaScript. To make changes:
1. Edit `index.html`
2. Commit and push changes to the main branch
3. GitHub Pages will automatically rebuild and deploy

## 📧 Contact
- Email: amcbfoundation@gmail.com
- Facebook: [AMCB Foundation](https://www.facebook.com/AMCB-Foundation-417097415151666/)

---

**AMCB Foundation Bangladesh** - Registered Non-Profit NGO
- Registration No. 3091
- Taxpayer Identification No. 448413744565
