# Much Ado About Love

Static one-page website for *Much Ado About Love*.

## Local Preview

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Project Structure

- `index.html` — page content
- `styles.css` — site styling and responsive layout
- `script.js` — reveal-on-scroll behavior
- `assets/media/` — local images used on the site

## Deployment

This is a plain static site. No build step is required.

### GitHub Pages

This project is set up to deploy the same simple way as your personal website:

- static files at the repo root
- no build process
- optional `CNAME` file if you later want a custom domain

Suggested steps:

1. Create a GitHub repository for this project.
2. Add the GitHub remote:

```bash
git remote add origin git@github.com:YOUR-USERNAME/YOUR-REPO.git
```

3. Stage and commit the site:

```bash
git add .
git commit -m "Initial site"
```

4. Push to GitHub:

```bash
git push -u origin main
```

5. In GitHub:

- open `Settings`
- open `Pages`
- set `Source` to `Deploy from a branch`
- choose `main`
- choose `/ (root)`

After that, GitHub Pages should publish the site directly from the root files.

### Custom Domain

If you want to mirror your personal site exactly with a custom domain, add a `CNAME`
file at the project root containing only your domain name, then configure the domain
inside GitHub Pages settings.
