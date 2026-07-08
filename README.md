# Ankit Patel — DevOps & SRE Lead Portfolio

Static GitHub Pages portfolio for **Ankit Patel** focused on DevOps, SRE, Kubernetes, GCP, Terraform, CI/CD, observability, incident response, platform engineering, and AI-driven operations.

## Live URL after deployment

```text
https://ankitpatel1234.github.io
```

## Repository name to use

Create this repository under your GitHub account:

```text
Ankitpatel1234.github.io
```

GitHub Pages uses the `username.github.io` repository naming pattern for a user site.

## Local preview

```bash
cd ankit-devops-sre-portfolio
python3 -m http.server 8080
```

Open:

```text
http://localhost:8080
```

## Deploy using Git CLI

```bash
git init
git add .
git commit -m "Create DevOps SRE portfolio"
git branch -M main
git remote add origin https://github.com/Ankitpatel1234/Ankitpatel1234.github.io.git
git push -u origin main
```

Then go to:

```text
https://ankitpatel1234.github.io
```

## Deploy using GitHub CLI

Install and login to GitHub CLI first:

```bash
gh auth login
```

Then from this folder:

```bash
gh repo create Ankitpatel1234.github.io --public --source=. --remote=origin --push
```

## Update content

Edit these files:

- `index.html` — portfolio sections and content
- `styles.css` — design, colors, layout
- `script.js` — mobile navigation behavior
- `sitemap.xml` and `robots.txt` — SEO metadata

## Recommended next improvements

- Add your latest resume PDF as `assets/Ankit_Patel_DevOps_SRE_Resume.pdf` and add a download button.
- Add screenshots/architecture diagrams for Terraform, Kubernetes, CI/CD and observability projects.
- Add links to polished GitHub repositories with production-grade README files.
- Add project case studies with problem, architecture, implementation, result, and interview talking points.
# ankit-devops-sre-portfolio
