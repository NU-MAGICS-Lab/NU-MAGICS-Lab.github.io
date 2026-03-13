# MAGICS Lab — NU-MAGICS-Lab.github.io

Website for the **MAGICS Lab** (Multi-Agent Intelligent Complex Systems) at Northeastern University's College of Engineering.

Hosted at: [https://nu-magics-lab.github.io/](https://nu-magics-lab.github.io/)

## Structure

```
/index.html          ← Single-page website (HTML + Tailwind CSS + JS)
/assets/images/      ← Place team photos and diagrams here
/README.md           ← This file
```

## Technology

- Pure static HTML — no build tools required
- [Tailwind CSS](https://tailwindcss.com/) via CDN (v3)
- [Lucide Icons](https://lucide.dev/) via CDN
- Google Fonts: Source Serif 4 + Source Sans 3

## Development

Open `index.html` directly in a browser, or serve locally with any static file server:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## Adding Content

- **Team photos**: Place images in `assets/images/` and update the placeholder `<div>` elements in `index.html`.
- **New team members**: Find the comment `<!-- Add additional team members ... -->` in the Team section.
- **Publications**: Update the Selected Publications area in the Research section.
- **News items**: Add new `<li class="news-item ...">` entries in the news list.
