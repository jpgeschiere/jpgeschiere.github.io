# JPG Works

Portfolio website for Jacobus Geschiere. Intended domain: jpgworks.dev.

## Run locally

Requires Python 3. From the repository root:

```sh
python -m http.server 8093 --directory dist
```

Open http://localhost:8093/en/ . No build or dependency installation is needed.

## Editing and hosting

Edit the HTML files in dist/en and dist/nl, shared dist/style.css, and dist/motion.js. Serve dist as the website root. Links assume root hosting, rather than a repository subpath.

Each clean route uses a directory with index.html. Matching legacy .html files contain the same content to avoid redirect loops on hosts that resolve extensionless URLs to .html. Keep these copies synchronized when editing.

English and Dutch pages, language preference, reduced-motion support, and the footer Snake easter egg are included. The intended domain is not configured by this repository.

Company logos, photographs, and publication material remain subject to their respective owners' rights.
