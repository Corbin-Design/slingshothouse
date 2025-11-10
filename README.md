[README.md](https://github.com/user-attachments/files/23458695/README.md)
# Slingshot House — One‑Page (CDN build)

Zero-build React + Tailwind version so you can drag/drop to GitHub Pages.

## Deploy to GitHub Pages (quick)
1. Create a new repo named `slingshot-house-site` (or anything).
2. Upload `index.html` to the repo root.
3. In the repo, go to **Settings → Pages**.
4. Under *Build and deployment*, set **Source** to *Deploy from a branch*.
5. Choose **branch: main** and **folder: /root** (or / for GitHub).
6. Save — the site will publish at `https://<your-username>.github.io/<repo>/`.

## Editing
- Open `index.html` and edit the JSX inside the `<script type="text/babel">` block.
- Tailwind is loaded via CDN, so you can use utility classes immediately.
- Images: later, paste URLs where you want them, or host in the repo and reference `./images/...`.

## Notes
- This build uses React 18 via CDN and Babel in the browser. For production, move to Vite/Next.
