# html-preview

A static HTML/CSS/JS previewer. **Share Link** copies a self-contained URL with the current preview compressed into its fragment. Nothing is published to the repository.

## Publishing a short link

1. Click **Short Link** and download the generated `<id>.json` file.
2. Upload the file without renaming it to `previews/` in this repository. Commit or merge it into `main`. You need repository write access.
3. After the existing GitHub Pages deployment finishes, share the URL shown in the dialog (`?p=<id>`).

Published previews are public snapshots, including their HTML source. Don't publish secrets or content you don't want in Git history. Edits in the app do not change a published snapshot; use **Share Link** to share edits without publishing, or create a new short link. Don't overwrite a previous snapshot with a different preview.

GitHub Pages already serves the root of `main`, including `previews/`. No extra workflow, API, or credentials in the browser are needed.
