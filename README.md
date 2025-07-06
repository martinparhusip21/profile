# Martin Parhusip Profile

This repository contains the source for Martin Parhusip's personal portfolio website. It is a static site built with HTML, CSS, and JavaScript.

## Local Development

You can open `index.html` directly in a browser to preview the site locally.

## Publishing with GitHub Pages

A GitHub Actions workflow is included to automatically publish the site to GitHub Pages whenever changes are pushed to the `main` branch.

1. Push this repository to GitHub.
2. In the repository **Settings** > **Pages**, choose **GitHub Actions** as the deployment source.
3. Make sure the workflow file `.github/workflows/gh-pages.yml` is present in the repository.
4. After pushing to `main`, the workflow will deploy the site to GitHub Pages. Your site will be available at:

```
https://<your-username>.github.io/<repository-name>/
```

