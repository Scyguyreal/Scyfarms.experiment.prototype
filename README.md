# Scyfarms Prototype

This repository contains a simple single-page social app called **Weave** built
using HTML, Tailwind CSS, and Parse (back4app) as a backend.

## Structure

- `index.html` – main application file. Edit this to change the UI or behavior.
- (previously `scyfarms.html` – now removed)

## Deployment

The site lives in this repository and is served by GitHub Pages from the `main`
branch root. After editing `index.html` (or adding assets), use the following
Git commands to update the site:

```bash
# stage your changes
git add index.html
# commit with an explanatory message
git commit -m "Describe your update"
# publish to GitHub
git push origin main
```

Once pushed, Pages will rebuild automatically; the current URL is:

> https://scyfarms.github.io/Scyfarms.experiment.prototype/

(If you have access to a repository named `scyfarms.github.io` you could push
there instead to serve as the root domain.)

## Editing and development

Open `index.html` in a text editor, make changes, and repeat the commit/push
cycle. You can preview changes locally by opening the file in your browser.

## Security considerations

The Parse initialization keys are embedded directly in the HTML. This is fine
for a prototype but should be replaced with a server or secret management
solution for a production app.

## Next steps

- Add error handling, form validation, and user profile pictures.
- Improve UX (loading indicators, animations).
- Move backend logic to a server to protect credentials.

Happy hacking! 🚀
