# bubblybingbong.github.io

Personal site for Ethan Kou — a single static page, no build step, no dependencies
beyond a Google Fonts stylesheet.

Live at <https://bubblybingbong.github.io/>.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | All content. Edit this to update text. |
| `styles.css` | All styling. Design tokens live in `:root` at the top. |
| `favicon.svg` | Monogram favicon. |

## Editing

Open `index.html` and edit in place — sections are marked with comment banners
(`HERO`, `RESEARCH`, `EXPERIENCE`, `PROJECTS`, `EDUCATION`, `SKILLS`, `CONTACT`).

To change the look, edit the custom properties at the top of `styles.css`:

```css
--accent: #6ee7b7;   /* links, badges, org names, section numbers */
--bg:     #0a0b0d;   /* page background */
--text:   #e7e9ee;   /* body text */
```

## Previewing locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying

Pushing to `main` publishes automatically once GitHub Pages is enabled
(Settings → Pages → Source: *Deploy from a branch* → `main` / `/root`).
