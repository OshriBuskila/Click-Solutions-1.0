# Click Solutions

A clean, modern static website starter — built with pure HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies.

## ✨ Features

- **Fully responsive** — mobile-first design with a collapsible navigation menu
- **Smooth scroll animations** — Intersection Observer-powered reveal effects
- **Dark theme** — sleek dark UI with CSS custom properties for easy theming
- **Animated hero** — gradient text, blurred blob backgrounds, and staggered content
- **Features & cards grid** — responsive grid layouts with hover effects
- **Contact form** — simulated async submission with success feedback
- **Zero dependencies** — no npm, no bundler, just open `index.html`

## 🗂 Structure

```
click-solutions/
├── index.html   # Main HTML
├── style.css    # All styles (CSS variables, layout, animations)
├── main.js      # Interactivity (nav, scroll reveal, form)
└── README.md
```

## 🚀 Getting Started

Simply open `index.html` in your browser — no build step needed.

```bash
# Or serve locally with any static file server, e.g.:
npx serve .
# or
python -m http.server
```

## 🎨 Customization

All colours are defined as CSS custom properties at the top of `style.css`:

```css
:root {
  --accent:   #6c63ff;   /* Primary accent */
  --accent-2: #ff6584;   /* Secondary accent */
  --bg:       #0d0d14;   /* Page background */
  ...
}
```

Change those values to instantly re-theme the entire site.

## 📄 License

MIT — use it however you like.
