# Neon Rail Rush

An original browser-based 3D endless runner built with Three.js and Vite.

## Run locally

```powershell
npm.cmd install
npm.cmd run dev
```

Open the URL printed by Vite (normally `http://localhost:5173`).

## Production build

```powershell
npm.cmd run build
npm.cmd run preview
```

## Controls

- Move: A/D or Left/Right arrows
- Jump: W, Up arrow, or Space
- Slide: S or Down arrow
- Mobile: swipe left/right/up/down

Progress, high scores, missions, upgrades, cosmetics, and settings persist in browser local storage.

## Publish with GitHub Pages

1. Create a new GitHub repository and upload this project (do not upload `node_modules`).
2. Use `main` as the repository's default branch.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **GitHub Actions** as the source.
5. Open the repository's **Actions** tab and wait for **Deploy game to GitHub Pages** to finish.
6. Your public game URL will be shown in the successful deployment and in **Settings → Pages**.

The usual URL format is:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/`
