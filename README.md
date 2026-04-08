# Mujicsx Digital Cassette

Static vintage cassette/vinyl message site built with HTML, CSS, and JavaScript.

## Local setup

Open `index.html` in your browser or run a local server:

```bash
cd mujicsx
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages deployment

1. Create a new GitHub repository for this project.
2. Add it as a remote and push:

```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

3. In GitHub repository settings, enable Pages from branch `main` and folder `/`.

The site will then be available at `https://<your-username>.github.io/<repo-name>/`.
