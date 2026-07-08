# Deployment Guide — Existing GitHub Pages Project Repo

Your portfolio repository:

```text
https://github.com/Ankitpatel1234/ankit-devops-sre-portfolio.git
```

Expected live URL:

```text
https://ankitpatel1234.github.io/ankit-devops-sre-portfolio/
```

## 1. Copy updated files into your local repo

```bash
git clone https://github.com/Ankitpatel1234/ankit-devops-sre-portfolio.git
cd ankit-devops-sre-portfolio
```

Copy all files from the updated package into this cloned folder.

## 2. Commit and push

```bash
git add .
git commit -m "Update portfolio email profile image and UI"
git push origin main
```

## 3. Enable GitHub Pages with Actions

Open your repository in GitHub, then go to:

```text
Settings → Pages → Build and deployment → Source
```

Select:

```text
GitHub Actions
```

## 4. Rerun deployment

Go to:

```text
Actions → Deploy static portfolio to GitHub Pages → Run workflow
```

## Notes

The workflow file is located here:

```text
.github/workflows/pages.yml
```

It uses GitHub Pages deployment actions and deploys the static website from the repository root.
