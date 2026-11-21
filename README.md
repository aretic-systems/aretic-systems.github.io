# aretic-systems.github.io

Website for Aretic Systems, served at https://areticsystems.com. The HAL marketing site (aimed at accelerator programs and investors) lives in `hal/` and is served at https://areticsystems.com/hal. Plain HTML/CSS, hosted on GitHub Pages.

- Edit `hal/index.html` (content) and `hal/styles.css` (look). No build step. The root `index.html` is a placeholder that forwards to `/hal/`.
- Preview locally: `python -m http.server 8000 --bind 127.0.0.1`, then open http://127.0.0.1:8000/hal/
- Every push to `main` redeploys the site.
