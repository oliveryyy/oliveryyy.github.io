# Dr. Oliver Yan - Academic Website

Academic personal website built with [Hugo](https://gohugo.io/) and [HugoBlox Academic](https://hugoblox.com/).

## Deployment

This site is deployed automatically to GitHub Pages via GitHub Actions.

### Steps to deploy:

1. Create a new repository named `oliveryyy.github.io` on GitHub
2. Push this code to the repository:

```bash
cd /Users/markyang/Desktop/OliverYan_website
git init
git add .
git commit -m "Initial commit: academic website"
git branch -M main
git remote add origin https://github.com/oliveryyy/oliveryyy.github.io.git
git push -u origin main
```

3. Go to the repository **Settings → Pages**
4. Under "Build and deployment", set Source to **GitHub Actions**
5. The site will be live at: https://oliveryyy.github.io/

## Local Development (Optional)

To preview locally, install [Hugo Extended](https://gohugo.io/installation/) and [Go](https://go.dev/dl/), then run:

```bash
hugo mod get
hugo server
```

## Customisation

- **Profile**: Edit `content/authors/admin/_index.md`
- **Homepage sections**: Edit `content/_index.md`
- **CV PDF**: Replace `static/uploads/resume.pdf`
- **Avatar photo**: Replace `content/authors/admin/avatar.jpg`
- **Site config**: Edit `hugo.yaml`
