# Toastmasters Club Flyer Studio

A single-page, mobile-first flyer generator for Toastmasters clubs. It renders 1536 × 1536 PNG flyers entirely in the browser and stores all club details, photos and saved members in `localStorage`.

## Publish to GitHub Pages

This folder is already initialized as a Git repository with an initial commit.

1. Create a new **public** repository on GitHub (do not add a README or `.gitignore`).
2. In this folder, run:

   ```powershell
   git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
   git push -u origin main
   ```

3. On GitHub, open the repository → **Settings** → **Pages**.
4. Set **Source** to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then save.
5. Your site will be live at `https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/`.

No build step is needed — `index.html` is the complete app.

## Notes

- Google Fonts (Montserrat and Source Sans 3) load from the CDN; everything else is self-contained.
- The club logo is embedded in the file by default and can be replaced from the editor.
- Because data is stored in the browser's `localStorage`, each visitor has their own private copy of club details and member photos; nothing is uploaded to a server.
