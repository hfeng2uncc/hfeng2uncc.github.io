# Hongsong Feng's academic website

This project adapts Rui Wang's public al-folio fork, including its about_custom layout and styles. It retains al-folio's MIT license in LICENSE. The site content is based on Hongsong Feng's Google Site. Review the content before publishing.

## GitHub Pages

1. Create a public repository named `hfeng2uncc.github.io`, then upload the complete contents of this folder including dotfiles and `.github`.
2. In Settings → Actions → General, allow GitHub Actions to read and write repository contents. The included deploy workflow builds on pushes to `main` or `master`, then publishes to the `gh-pages` branch. Check Actions for build errors.
3. In Settings → Pages, select Deploy from a branch, branch `gh-pages`, folder `/ (root)`. The branch appears after the first successful build. The eventual address is https://hfeng2uncc.github.io/.

These steps may require a repository administrator. Publishing on GitHub Pages is public.

Edit `_pages/about.md`, `_data/research_interests.yml`, and the other files in `_pages` to update content. Add a profile image to `assets/img/` and configure `profile` in `_pages/about.md` if desired. Course codes are omitted pending verification. The CV is a concise web page, not a PDF.
