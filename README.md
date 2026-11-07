# Sanskriti Singh – Personal Portfolio

A single-page personal portfolio website built with **HTML5 and CSS3 only** for the Web Development assignment at IIM Sirmaur. No frameworks and no JavaScript are used.

## Project structure

```
personal-portfolio/
├── index.html        Page content and structure
├── style.css         All styling (external stylesheet)
├── assets/
│   └── resume.pdf    Resume used by the "Download resume" button
└── README.md         This file
```

## Sections

| Section | Purpose |
|---|---|
| Navigation bar | Sticky bar with the wordmark and links to every section |
| Hero | Name, academic identity, short introduction and two buttons |
| About | Short background and what I am looking for |
| Education | Timeline of IIM Sirmaur, IIM Bangalore and school |
| Skills | Skills grouped by category, plus languages |
| Projects | Four academic research projects in a grid of cards |
| Experience | Positions of responsibility, work and volunteering |
| Achievements | Certifications and simulations completed |
| Contact | Email, GitHub and location, followed by a footer |

## Running locally

1. Download or unzip the project folder.
2. Double-click `index.html` to open it in a browser.

An internet connection is needed only for the Google Fonts (Playfair Display and Inter). Without it, Georgia and Arial are used instead.

## Hosting on GitHub Pages

1. Upload the contents of this folder to the root of the repository (`index.html` must be at the top level, not inside a sub-folder).
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute or two the site is available at `https://<username>.github.io/<repository-name>/`.

All file paths in the project are relative, so it works on GitHub Pages without changes.

## CSS concepts demonstrated

- Universal selector (`*`), element, class and ID selectors (`#site-header`)
- CSS variables in `:root` for colours, fonts and sizes
- Typography: `font-family`, `font-size`, `font-weight`, `line-height`, `letter-spacing`, `text-transform`, `text-align`
- Colours, backgrounds, margin, padding, borders, `border-radius`, `box-shadow`, `box-sizing`
- `display`: block, inline-block, flex and grid
- Flexbox for the navigation bar, buttons, role headings and footer
- CSS Grid for About, Skills, Projects, Experience, Certifications and Contact
- Positioning: `sticky` (header), `relative` and `absolute` (nav underline, timeline dots, bullets)
- Hover and transition effects on links, buttons and cards
- Media queries at 1000px, 860px and 560px for laptops, tablets and phones

## Content notes

All content comes from the resume. The phone number and any street address are deliberately not shown on the page.
