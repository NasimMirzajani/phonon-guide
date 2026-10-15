# Phonons & Polaritons — Research Guide

## One-time setup (GitHub Pages)

1. Create a **public** repository named `phonon-guide` on GitHub (without a README or license).
2. Unzip the starter ZIP. Upload **the contents of the `phonon-guide` folder**, preserving directories, into the repository using **Add file → Upload files**; commit to `main`. (If your browser does not accept folders, upload with GitHub Desktop or git.)
3. In the repository open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. The guide should appear at `https://YOUR_USERNAME.github.io/phonon-guide/` after publishing completes.

## Publish the next lesson

Ask ChatGPT: “Export briefing 04 as a Jekyll Markdown file for my phonon-guide website, following the existing lesson template, with YAML front matter and MathJax-compatible equations.” Download the `.md` file and upload it to `lessons/` in your GitHub repository, then commit. GitHub Pages rebuilds the navigation automatically. No manual HTML formatting or sidebar editing.

## Why Markdown instead of copying HTML?

Jekyll (included with GitHub Pages) converts Markdown into styled HTML; the global `_layouts/default.html` handles the persistent sidebar, and enumerates lesson pages using their `lesson_number` in the front matter. If you do want raw HTML, it can also be added with YAML front matter and the same fields.

## Note on file hosting

The public GitHub Pages repo makes the lessons publicly viewable. Avoid storing private content. If you rename the repository, update `baseurl` in `_config.yml` to match, or use `baseurl: ""` for a user-site repository.
