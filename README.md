# Portfolio – Moch. Agung Anugrah

Static portfolio site (HTML, CSS, JS only; no build step).

## Deploy to GitHub Pages
1. Create a new public repository on GitHub, e.g. `agung-portfolio`
   (or `<username>.github.io` for a root URL).
2. Upload `index.html`, `README.md` and the `assets/` folder to the repository root.
3. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**,
   select `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<username>.github.io/<repo-name>/`.

## Editing
- All content is in `index.html`. Each role is a `<details class="job">` block.
- The career timeline reads from the `lanes` array near the bottom of the file.
  Add the new role there (start/end as fractional years) when you add a job.
- Replace `assets/foto.jpg` to change the portrait.
