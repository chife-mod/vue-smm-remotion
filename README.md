# VUE SMM — Social Media Ad Campaign

Internal preview dashboard for VUE (EnergyPlus Building Intelligence Platform)
social-media ad creatives. Static slides first, then animated as a Remotion
carousel.

**Live:** https://chife-mod.github.io/vue-smm-remotion/

## Structure

```
/
├── index.html             # launcher (Wireframe + Design slots)
├── assets/logo.svg        # placeholder brand mark — replace before client demos
├── shared/                # design tokens, components, chip nav
│   ├── tokens.css
│   ├── components.css
│   ├── service-menu.css
│   └── service-menu.js
└── uikit/index.html       # tokens & components reference (hidden, direct URL)
```

## Local preview

```sh
python3 -m http.server 5180
# open http://localhost:5180/
```

## Roadmap (project stages)

1. Wireframe — static slide structure & copy
2. Design — visual treatment of approved wireframes
3. Static slides — built from Figma, with PDF export button
4. Remotion — animate the static slides as a carousel
5. Export — final mp4 + PDF assets
