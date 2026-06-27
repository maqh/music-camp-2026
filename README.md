# Music Camp — GitHub Pages publish instructions

This folder contains the parent information pack HTML for Music Camp 2026.

To publish with GitHub Pages (user or project site):

1. Initialize a git repo and commit the files:

```bash
cd /home/miki/KeepApp/music-camp
git init
git add index.html 2026-parent-pack.html README.md
git commit -m "Add parent pack for Music Camp 2026"
```

2. Create a new GitHub repository (on github.com) named `music-camp` (or your preferred name), then add the remote and push:

```bash
git remote add origin git@github.com:<your-username>/music-camp.git
git branch -M main
git push -u origin main
```

If you prefer HTTPS:

```bash
git remote add origin https://github.com/<your-username>/music-camp.git
git push -u origin main
```

3. Enable GitHub Pages:

- Go to the repository Settings → Pages.
- Under "Build and deployment" choose "Deploy from a branch".
- Select branch `main` and folder `/ (root)`.
- Save — your site will be published at `https://<your-username>.github.io/<repo>/`.

4. The page will be available at:

`https://<your-username>.github.io/<repo>/index.html`

Optional: rename `index.html` to `index.html` (already set), or create a simple `404.html` for nicer redirects.

If you want, I can:

- Create the local git repo and make the initial commit (done).
- Help push to GitHub if you provide a remote URL or a Personal Access Token (instructions provided above).
- Set up a custom domain via Cloudflare once Pages is live.

Tell me which next step you'd like me to do: push to GitHub, or show the commands to run locally.
