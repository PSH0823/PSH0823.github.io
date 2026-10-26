# Sanghyuk Park homepage

Static files for `PSH0823.github.io`. GitHub Pages should publish from the `main` branch's `/ (root)` folder.

## Update the website

1. Edit the source files in `../site/dist/` or replace `../SanghyukPark_CV.pdf`.
2. Run `../sync-github-pages.sh` from this directory. This copies the current website and CV into this repository.
3. Review and publish:

```bash
git status
git add .
git commit -m "Update homepage"
git push -u origin main
```

A replacement PDF does not update the hosted website until the new file is copied, committed, and pushed.
