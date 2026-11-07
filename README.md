# Sanskriti Singh – Personal Portfolio

A single-page personal portfolio website built with **HTML5 and CSS3 only** for the Web Development assignment at IIM Sirmaur. No frameworks and no JavaScript are used.

Live site: https://sanskriti8761-max.github.io/sanskriti-portfolio/

## Project structure

```
sanskriti-portfolio/
├── index.html          Page content and structure (must stay in the root)
├── style.css           All styling (external stylesheet)
├── assets/
│   ├── profile.jpg     Photograph used in the hero section
│   └── resume.pdf      Resume used by the "Download resume" button
└── README.md           This file
```

## Sections

| Section | Purpose |
|---|---|
| Navigation bar | Sticky bar with the wordmark and links to each section |
| Hero | Name, positioning line, introduction, photograph and two buttons |
| About | Academic journey, interests, campus roles and mentoring |
| Education | Timeline of IIM Sirmaur, IIM Bangalore and school |
| Skills | Four groups: Business & Management, Research & Analytical, Creative & Digital, Communication |
| Projects | Six project cards plus additional academic and creative work |
| Explore My Work | Button to the full Google Drive portfolio (opens in a new tab) |
| Experience | Positions of responsibility, work and volunteering |
| Achievements | Certifications and simulations |
| Hobbies & Interests | Six short interest cards |
| Contact | Email, GitHub, LinkedIn and location, then a footer |

## Running locally

1. Download or unzip the project folder.
2. Double-click `index.html` to open it in a browser.

An internet connection is needed only for the Google Fonts (Playfair Display and Inter). Without it, Georgia and Arial are used instead.

## Updating the GitHub repository

1. Open https://github.com/sanskriti8761-max/sanskriti-portfolio and click **Add file → Upload files**.
2. Drag in `index.html`, `style.css` and the `assets` folder from the unzipped project (not the ZIP file or the outer folder).
3. Confirm that files with the same name are replaced, write a short commit message and click **Commit changes**.
4. GitHub Pages republishes automatically after a minute or two. No Pages settings need to change.

All file paths are relative, so the site works on GitHub Pages without changes.

## CSS concepts demonstrated

- Universal selector (`*`), element, class and ID selectors (`#site-header`)
- CSS variables in `:root` for colours, fonts and sizes
- Typography: `font-family`, `font-size`, `font-weight`, `line-height`, `letter-spacing`, `text-transform`, `text-align`
- Colours, backgrounds, margin, padding, borders, `border-radius`, `box-shadow`, `box-sizing`
- `display`: block, inline-block, flex and grid
- Flexbox for the navigation bar, buttons, role headings and footer
- CSS Grid for the hero, About, Skills, Projects, Experience, Certifications, Interests and Contact
- Positioning: `sticky` (header), `relative` and `absolute` (nav underline, timeline dots, bullets)
- `object-fit` and `aspect-ratio` for the circular hero photograph
- Hover and transition effects on links, buttons and cards
- Media queries at 1000px, 860px and 560px for laptops, tablets and phones

## Content notes

Content comes from the resume and from details provided directly. The phone number and street address are deliberately not shown.
