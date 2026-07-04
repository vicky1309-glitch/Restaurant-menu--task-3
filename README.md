# Nocturne — Fine Dining Website

## How to run this in VS Code

1. Unzip this folder and open it in VS Code (`File > Open Folder...`).
2. Install the **Live Server** extension (by Ritwick Dey) from the Extensions panel, if you don't already have it.
3. Right-click `index.html` in the file explorer and choose **"Open with Live Server"**.
4. Your browser will open the site automatically at something like `http://127.0.0.1:5500`.

Alternatively, you can just double-click `index.html` to open it directly in your browser — no server needed, since it's a single self-contained file.

## Notes

- Everything (styles, scripts, and the two restaurant photos) is bundled into this one `index.html` file — no other files or folders are needed.
- The Menu, Signature Dishes, and Gallery sections pull some food/drink photos live from free public APIs (Foodish, TheMealDB, TheCocktailDB) when the page loads, so an internet connection is needed to see those images. The hero background and two gallery ambience photos are embedded directly and always work offline.
- To publish this for free, you can push this folder to a GitHub repository and enable **GitHub Pages** (Settings → Pages → Deploy from branch → main → /root).
