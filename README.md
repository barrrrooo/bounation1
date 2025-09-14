# OBJ Viewer – GitHub Pages Starter

This repo is a static site you can publish on **GitHub Pages** to view `.obj` (and optional `.mtl`) models in the browser.

## Deploy (GitHub Pages)
1. Create a **public** repo on GitHub (e.g., `obj-viewer`).
2. Upload all files from this folder, keeping the same structure.
3. Go to **Settings → Pages → Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` and **Folder:** `/ (root)`
4. Open your site at: `https://<your-user>.github.io/<repo>/`

## Add your model
- Put your files at `assets/model.obj` (and `assets/model.mtl` if you have materials).
- Make sure textures referenced in the `.mtl` are placed in `assets/` too.
- Keep file sizes small for the web (consider converting to glTF/GLB or simplifying meshes).

## Notes
- GitHub has a hard limit of ~100 MB per file. Stay under that for smooth deployment.
- Use **relative paths** so the site works on subpaths (GitHub Pages project sites).


This variant uses **A-Frame** and its built-in `obj-model` component.
