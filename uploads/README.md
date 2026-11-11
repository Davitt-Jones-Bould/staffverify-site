# uploads/

Resources used by `index.html`. Paths are relative, so the site works from any
GitHub Pages URL (user site or project site).

## Already here

| File | Used for |
| --- | --- |
| `logo.svg` | Favicon, and the header mark until you add `icon.png` |
| `fonts/bricolage-grotesque.woff2` | Headings and code digits (SIL Open Font License) |
| `fonts/atkinson-400.woff2`, `fonts/atkinson-700.woff2` | Body text (SIL Open Font License) |

## Drop these in and they appear automatically

| File name | What it is | Where it shows |
| --- | --- | --- |
| `icon.png` | The real app icon, square, 256px or larger | Replaces the mark in the header |
| `screenshot-1.png` | App screenshot: the code screen | New "The app today" section |
| `screenshot-2.png` | App screenshot: the verify screen | Same section |

The page checks for each file when it loads. If a file is missing, nothing
breaks: the header keeps the placeholder mark and the screenshot section stays
hidden. File names are case-sensitive on GitHub Pages.
