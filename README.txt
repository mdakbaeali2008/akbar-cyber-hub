AKBAR CYBER HUB — GITHUB PAGES FIX

This package contains ONE workflow file. It does not delete or replace your existing website files.

UPLOAD THIS FILE TO YOUR REPOSITORY AT EXACTLY:
.github/workflows/pages.yml

Then go to:
Repository -> Settings -> Pages -> Build and deployment -> Source -> GitHub Actions

Do NOT select main /docs after switching to Actions.

After you save the workflow file, GitHub Actions will publish the existing site.
It uses docs/ if docs/index.html exists. Otherwise it uses the repository root if index.html exists.

This is designed to bypass the Jekyll/SCSS build problem while keeping your existing files.
