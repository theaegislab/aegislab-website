# The Aegis Lab website

Jekyll site (bulma-clean-theme), deployed to GitHub Pages at https://aegislab.bio.

## Making changes live

1. Preview locally: `bundle exec jekyll serve`, open http://127.0.0.1:4000
2. Commit and push to `main`:
   ```
   git add -A
   git commit -m "..."
   git push
   ```
3. That's it. Pushing to `main` triggers `.github/workflows/pages.yml`, which
   builds the site and deploys it to GitHub Pages automatically. Check
   progress with `gh run watch --repo theaegislab/aegislab-website`, or in
   the repo's Actions tab. The build+deploy takes about a minute; the live
   site updates right after.

No DNS/Namecheap steps are needed for routine content changes — that setup
is one-time and already done.
