# Li June Choi — Portfolio

Static portfolio site. Plain HTML and CSS: no build step, no dependencies.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home |
| `resume.html` | Resume |
| `motorola.html` | Motorola projects |
| `valentine.html` | be my moto valentine |
| `fifa.html` | razr × FIFA World Cup 26 |
| `typography.html` | Typography projects |
| `agent.html` | AGENT |
| `gat.html` | Gat (갓) |

Images are in `images/`. Shared mobile layout rules are in `site.css`; each page keeps its own styles in its `<head>`.

## Publish on GitHub Pages

1. Create a new repository on GitHub. Name it `<your-username>.github.io` to host it at `https://<your-username>.github.io`, or use any name to host it at `https://<your-username>.github.io/<repo-name>`.
2. Upload everything in this folder to the repository root (drag the files into **Add file → Upload files**, or push with git).
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, pick **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. After a minute or two, the site is live at the address shown on that page.

With git:

```bash
cd lijune-portfolio
git init
git add .
git commit -m "Portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Editing

Open any `.html` file in a text editor. To swap an image, replace the file in `images/` with one of the same name, or change the `src` in the page. Fonts (Bricolage Grotesque and Instrument Sans) load from Google Fonts.
