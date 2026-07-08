# Deployment Guide — GitHub Pages

## Option 1: User site repository

1. Create a new repository named exactly:

```text
Ankitpatel1234.github.io
```

2. Upload all files from this portfolio folder.
3. Commit the files to the `main` branch.
4. Open:

```text
https://ankitpatel1234.github.io
```

GitHub usually publishes a `username.github.io` repository automatically. If the site is not live after a few minutes, check **Repository → Settings → Pages** and set the source to `main` branch and `/root` folder.

## Option 2: Existing repository project site

1. Create or open a repository such as:

```text
portfolio
```

2. Push these files to the repository.
3. Go to **Settings → Pages**.
4. Select **Deploy from branch**.
5. Choose branch `main` and folder `/root`.
6. The site URL will look like:

```text
https://ankitpatel1234.github.io/portfolio/
```

If you deploy under a project repository instead of `Ankitpatel1234.github.io`, update these fields in `index.html`, `robots.txt`, and `sitemap.xml`:

```text
https://ankitpatel1234.github.io
```

to:

```text
https://ankitpatel1234.github.io/portfolio/
```

## Recommended GitHub profile update

Create a separate repository named exactly:

```text
Ankitpatel1234
```

Then copy the content from:

```text
GITHUB_PROFILE_README.md
```

into that repository's `README.md`. This will show directly on your GitHub profile page.
