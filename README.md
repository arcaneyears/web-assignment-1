# Assignment #1 — HTML & CSS Basics

A personal webpage built with plain HTML and CSS for the Web Technologies course
at Astana IT University.

**Author:** Yersain Taubay
**Group:** SE2524

## Live demo

https://arcaneyears.github.io/web-assignment-1/

## Project structure

```
.
├── index.html          # Task 1 — personal webpage
├── task2.html          # placeholder page for the next task
├── styles.css          # all styling for every page
├── images/
│   └── profile.svg     # profile picture (replace with your own photo)
└── README.md
```

## What Task 1 contains

- `h1` and `h2` headings
- Three paragraphs of text
- An ordered list with 5 items and unordered lists with 5 and 3 items
- An image with an `alt` attribute
- Three external links with a hover effect
- A profile card with photo, name, group and short description
- A navigation bar linking to the separate task pages

## CSS techniques used

| Requirement | Where |
|---|---|
| Background colour | `body { background-color: var(--bg) }` |
| Font family, size, colour | `body`, `h1`, `h2`, `p` |
| Margin, padding, border | `.card`, `.profile-card`, `.container` |
| `border-radius` + `max-width` on image | `.avatar`, `img` |
| Link hover effect | `a:hover`, `.nav-link:hover` |
| Element selector | `body`, `h1`, `p`, `a`, `img` |
| Class selector | `.card`, `.navbar`, `.profile-card`, `.tools` |
| ID selector | `#page-title` |
| Responsive layout | `@media (max-width: 600px)` |

## Running locally

No build step and no dependencies — just open the file:

```bash
git clone https://github.com/arcaneyears/web-assignment-1.git
cd web-assignment-1
xdg-open index.html      # macOS: open index.html
```

## Publishing with GitHub Pages

1. Push the project to a GitHub repository.
2. Open **Settings → Pages** in the repository.
3. Under *Build and deployment*, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then press **Save**.
5. After a minute the site is available at
   `https://arcaneyears.github.io/web-assignment-1/`.
