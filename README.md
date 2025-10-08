# Video → Countdown (GitHub Pages)

Files:
- `index.html` — embeds a Google Drive video. Replace `REPLACE_WITH_FILE_ID` with your Google Drive file ID after making the file shareable ("Anyone with the link" - Viewer).
- `countdown.html` — black page with a big white 7-day countdown.

Quick steps:
1. Create a GitHub account at https://github.com (if you don't already have one).
2. Create a new repository named exactly: `USERNAME.github.io` (replace `USERNAME` with your GitHub username). **Repository must be public.**
3. Upload `index.html` and `countdown.html` to the root of that repository. Commit the change.
4. Open `https://USERNAME.github.io` in your browser (replace `USERNAME`).
5. If the page 404s, double-check:
   - The repo name is exactly `USERNAME.github.io`
   - `index.html` is in the repository root
   - The repository is public
   - Your Google Drive file is shared to "Anyone with the link" and you replaced the FILE_ID correctly.

If Google Drive embedding causes problems (large file or download limits), consider uploading the video to YouTube as "Unlisted" and embedding via an `<iframe>` instead.
