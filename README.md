# cloudyv

**Cloudy Tone** is a creator and model portfolio based in Mirzapur. The single-page site in `index.html` presents an introduction, services, selected work, collaboration information, and contact or booking sections.

## Preview locally

Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Page resources and publishing

The page references Cormorant Garamond and Manrope through Fontsource URLs; these font requests require network access. Inspect `index.html` for the actual image and other asset references. The supplied repository details do not establish that separate local assets exist.

The page’s HTML and client-side values are delivered to visitors. Do not put secrets in `index.html`. Before publishing, confirm that contact details, booking destinations, and portfolio media are intended to be public; do not add private or unapproved media to tracked files.

No deployment configuration or publishing settings are identified in the supplied repository details. Check the publishing target’s actual document or output directory rather than assuming a build step or routing behavior. After publishing, review the page and confirm local references and contact or booking destinations in that context.

## Editing and troubleshooting

Make content, style, link, or media-reference changes in `index.html`. Preserve relative paths, updating them deliberately when replacing or moving assets. If content or styling is missing, inspect the page’s references and check the browser Console and Network panel for errors or failed requests. Confirm displayed contact details and link destinations before relying on them.

- `index.html` — HTML page entry point and portfolio content.
- `README.md` — project documentation.