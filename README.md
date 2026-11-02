# Jalu Veda — project portfolio site

A static site: `index.html` plus `assets/`. No build step.

## Deploy on GitHub Pages
1. Create a repository named `19Jal.github.io` (or any name).
2. Upload `index.html`, `README.md` and the `assets/` folder to the repository root.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site appears at `https://19jal.github.io` (or `https://19jal.github.io/<repo-name>`).

Netlify or Vercel also work: drag the folder onto Netlify Drop (app.netlify.com/drop).

## Before you publish
- `assets/Jalu-Veda-CV.pdf` is your AI/ML CV and includes your phone number. Replace it with a version without the number if you don't want it public.
- Confirm with your advisor that the TSMC project description is cleared for public posting.

## Editing
- Each project is an `<article>` in `index.html`. The `data-tags` attribute decides which stage(s) of the hero diagram it belongs to: `pcb`, `firmware`, `control`, `digital`, `ml`, `deploy`. Counts update automatically.
- Images live in `assets/img/`. Any button with class `zoom` and a `data-full` attribute opens that image enlarged.
