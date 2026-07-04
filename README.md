# GitHub Pages Deployment

This repository is ready to publish as a static site with GitHub Pages.

## Structure

- `index.html` is now a lightweight landing page for navigation.
- `Report Designs/Post Report/skill-movement-designs.html` remains the actual design page.
- Add future pages as separate HTML files, then link them from `index.html`.

## Publish steps

1. Create a GitHub repository.
2. Push this folder to the `main` branch.
3. In GitHub, open `Settings` -> `Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Set `Branch` to `main` and folder to `/ (root)`.
6. Save and wait a minute or two.

Your site URL will be visible on the Github -> Setting -> Pages

## Suggested git commands

```bash
git add .
git commit -m "Prepare site for GitHub Pages"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```
