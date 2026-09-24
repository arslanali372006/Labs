# Arslan Ali — Personal Portfolio

A 5-page personal portfolio website built with plain HTML5 and CSS3.

**Live site:** _add your GitHub Pages link here after deploying_

## Pages

- `index.html` — Home
- `hobbies.html` — Hobbies
- `skills.html` — Skills
- `gallery.html` — Image gallery
- `contact.html` — Contact

## Project structure

```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── profile.jpeg
│   ├── image1.jpeg
│   ├── image2.jpeg
│   ├── image3.jpeg
│   ├── image4.jpeg
│   └── image5.jpeg
└── README.md
```

## Notes

- All styling lives in `css/style.css` — no inline styles, no CSS frameworks, no JavaScript.
- The navigation menu, the home page hero (profile photo beside text), and the image
  gallery are laid out with `float`, with `clear` used to contain each floated section.
- Layout is responsive down to mobile via media queries.

## Deployment

1. `git init`
2. `git add .`
3. `git commit -m "Portfolio: external CSS, float/clear layout"`
4. Push to GitHub, then enable **GitHub Pages** from the repo's Settings.
