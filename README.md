# The VIBE New England: website

Plain HTML and CSS, hosted free on GitHub Pages. There is no build step and nothing to install.

Live site: https://vibenewengland.github.io/site/

## How to edit (no software needed)

1. Sign in to GitHub and open this repo.
2. Click a file (for example `index.html`), then the pencil icon (Edit).
3. Change the text, then click **Commit changes**. The site updates in about a minute.

| To change...       | Edit...                                                               |
|--------------------|-----------------------------------------------------------------------|
| A member's bio     | `index.html`, find their `<article class="member">`                   |
| Phone / email      | `index.html`, the `Book The VIBE` section near the bottom             |
| Band name          | `index.html`, search for `The VIBE New England` and replace each one  |
| Colors             | `style.css`, the `:root { ... }` block at the top                     |
| A photo            | `assets/img/`: **Add file > Upload files**, then update `src="..."`   |

Keep photos under about 1 MB each so the page loads fast.

## Changing the name or domain later

- Name: see the table above.
- Custom domain: buy it at an independent registrar, add a file named `CNAME` containing the
  domain, then follow GitHub's Settings > Pages instructions for DNS.
