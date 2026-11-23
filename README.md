# Dr Safwat MRCOG Part 2 Question Bank

A static, mobile-friendly practice website. Open via a web server (e.g. `python -m http.server 8000`), not directly as a file, because it loads `questions.json`.

## Publish for free with GitHub Pages
1. Create a GitHub repository and upload `index.html` and `questions.json` at the repository root.
2. In repository Settings → Pages, select **Deploy from a branch**, `main`, `/ (root)`.
3. The public URL will normally be `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/` after GitHub publishes it. This is a URL pattern, **not an active link**.

## Daily updates
The website loads `questions.json` each time it opens, so published edits appear automatically. **There is no unattended daily content generation in this starter project.** To update daily, a responsible editor must review authoritative sources, write original questions, validate the source URLs and dates, and commit revised JSON. Do not use confidential recalls or copyrighted question banks. A scheduled GitHub Action or other backend can be added after repository access and editorial workflow are configured.

## Data
Answers are stored locally in the user's browser; no accounts or server-side sync. Questions marked `Needs independent guideline verification` are starter examples and not yet certified against the latest source versions.
