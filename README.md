# academic-website-v1.0
First try creating an academic website with the help from this youtube series: https://www.youtube.com/playlist?list=PLpZT7JPM8_GbPiX4ibrP7ogl7GyEofZMj and, of course, ChatGPT

## Working on the site

The site is built with [Hugo](https://gohugo.io) (extended edition, version 0.167.0) and the Wowchemy Academic theme, and is published on Netlify whenever `main` is pushed to GitHub.

1. Install Hugo extended. On Windows: `winget install Hugo.Hugo.Extended`
2. In this folder, run `hugo server` and open http://localhost:1313
3. Edit files under `content/` (your profile is `content/authors/admin/_index.md`) and `config/_default/`. The preview refreshes on save.
4. Commit and push to `main` to publish.

The theme lives in `themes/` and was patched to build on current Hugo versions.
