# Assignment #1 — HTML & CSS Basics

**Author:** Yersaiyn Taubay
**Group:** SE2524
**Course:** Web Technologies — Astana IT University

A small static website made with plain HTML and CSS. It contains four pages,
one for each task of the assignment, linked together by a navigation bar.

## Live demo

https://zippy-eclair-b2c532.netlify.app/

## Pages

| Page | Task | Description |
|---|---|---|
| `index.html` | Task 1 | Personal page with a profile card, lists, image and links |
| `task2.html` | Task 2 | Two-column layout built only with `div` and `float` (no flexbox, no grid) |
| `exercise1/index.html` | Task 3 | Tribute page for Nikola Tesla, two Google Fonts |
| `task4.html` | Task 4 | Styled grade table with merged cells and a feedback form |

## Project structure

```
.
├── index.html          # Task 1
├── styles.css
├── task2.html          # Task 2
├── task2.css
├── task4.html          # Task 4
├── task4.css
├── exercise1/          # Task 3
│   ├── index.html
│   ├── styles.css
│   └── images/tesla.jpg
├── images/profile.jpg
├── report/report.html  # report with screenshots
└── README.md
```

## What each task demonstrates

- **Task 1** — element, class and ID selectors, background colour, fonts,
  margins, padding, borders, `border-radius`, hover effect, media query.
- **Task 2** — page layout with floats, `clear`, box shadows, styled navigation.
- **Task 3** — Google Fonts, gradient background, centred container,
  `list-style-type`, styled image and button.
- **Task 4** — `border-collapse`, `nth-child` striping, `rowspan` / `colspan`,
  a highlighted row, and a fully styled form.

## Running locally

```bash
git clone https://github.com/arcaneyears/web-assignment-1.git
cd web-assignment-1
xdg-open index.html      # macOS: open index.html
```

Or serve the folder so that all relative links work:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080 in a browser.
