# Alok – Personal Portfolio

Responsive portfolio website built with HTML5, CSS3 and Vanilla JavaScript.
No build process or backend needed – works directly on GitHub Pages.

## Folder Structure
- `index.html` – all page content (edit text here)
- `css/style.css` – styles and theme colours (variables at top)
- `js/script.js` – theme toggle, mobile menu, animations
- `assets/images/` – `profile.jpg`, `ai-literacy.png`, project images
- `assets/documents/resume.pdf` – downloadable resume

## Setup
1. Rename and place your files:
   - `Prof_Image.jpeg` → `assets/images/profile.jpg`
   - `ai-literacy__1_.png` → `assets/images/ai-literacy.png`
   - `Alok_CV.pdf` → `assets/documents/resume.pdf`
2. Open `index.html` in a browser to preview locally.

## Deploy on GitHub Pages
1. Create a repository (e.g. `Allok3052.github.io` or `portfolio`).
2. Upload all files keeping the same folder structure.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Your site will be live at `https://allok3052.github.io/` (or `/portfolio/`).

## How to Update
- **Add a project:** copy a `<article class="card project-card">` block in the Projects section.
- **Add a certificate:** copy a `<article class="card cert-card">` block in Certifications.
- **Project image:** replace the placeholder `<div>` with `<img src="assets/images/yourimage.jpg" alt="...">`.
- **Colours:** edit the variables at the top of `css/style.css`.
