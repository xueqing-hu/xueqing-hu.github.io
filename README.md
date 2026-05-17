# Xueqing Hu — Academic Homepage

A compact, one-page academic website for GitHub Pages.

## Files

- `index.html` — main content. Most future updates happen here.
- `assets/styles.css` — visual style.
- `.nojekyll` — tells GitHub Pages to publish the static files directly.

## Fastest deployment

### Option A — Personal GitHub Pages site

1. Create a new GitHub repository named:

   ```text
   YOUR-GITHUB-USERNAME.github.io
   ```

2. Upload all files in this folder to the repository root.

3. Commit the files.

4. Open:

   ```text
   https://YOUR-GITHUB-USERNAME.github.io
   ```

### Option B — Project site

1. Create any repository, for example:

   ```text
   academic-homepage
   ```

2. Upload all files in this folder to the repository root.

3. Go to **Settings → Pages**.

4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`

5. Open:

   ```text
   https://YOUR-GITHUB-USERNAME.github.io/academic-homepage/
   ```

## Before publishing

Search in `index.html` for:

```text
[Your MSc university]
[Title of your MSc-related paper]
```

Replace these placeholders with final information.

Also replace the `#` links for Google Scholar, ORCID, and GitHub when ready.
