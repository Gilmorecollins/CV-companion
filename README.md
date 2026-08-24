# CV Companion

A single-page, responsive CV/portfolio site for **Collins Kipkemboi** — Software Engineer & UX/UI Designer based in Eldoret, Kenya.

## Features

- **Light/dark theme** toggle, saved to `localStorage`, with a theme-aware hero photo that swaps between a light and dark background image
- **Responsive layout** — collapses to a mobile nav menu and single-column sections below 720px
- **Scroll-reveal animations** for sections and skill bars via `IntersectionObserver`
- Sections: Profile, Experience, Skills, Projects, Education & Certifications, Contact
- Project cards link out to their individual [GitHub repos](https://github.com/Gilmorecollins)
- No build step, no dependencies — a single self-contained `index.html`

## Tech stack

- Vanilla HTML, CSS, and JavaScript
- [Manrope](https://fonts.google.com/specimen/Manrope) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts
- Images embedded inline as base64 data URIs (no external asset requests)

## Running locally

No build tools required — just open the file directly:

```
start index.html
```

Or serve it locally (needed for some browser security contexts):

```
npx serve .
```

## Customization

Theme colors are defined as CSS custom properties at the top of `index.html`:

```css
:root{
  --bg:#FAFAF7;
  --accent:#3D52A0;
  ...
}
:root[data-theme="dark"]{
  --bg:#0B0D12;
  ...
}
```

Update these to re-theme the whole site.

## Contact

- Email: collinskorirpk37.ck@gmail.com
- LinkedIn: [collins-kipkemboi](https://www.linkedin.com/in/collins-kipkemboi-0456a3245)
- GitHub: [Gilmorecollins](https://github.com/Gilmorecollins)
