# DFT Master Dashboard

Interactive single-page DFT learning dashboard for beginner to advanced engineers.

## Local preview

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080/docs/`.

## GitHub Pages deployment (recommended)

1. Push this repository to a **public GitHub repository**.
2. In GitHub, open **Settings -> Pages**.
3. Under **Build and deployment**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your published branch)
   - **Folder**: `/docs`
4. Save and wait for deployment.
5. Public URL will be:

```text
https://<github-username>.github.io/<repo-name>/
```

## Notes

- Dashboard source is at `docs/index.html`.
- No framework or build step required.
- `.nojekyll` is included so GitHub Pages serves files directly.
