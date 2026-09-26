# Lumina — Interactive Image Gallery

A responsive, modern image gallery built with semantic HTML5, Tailwind CSS, and vanilla JavaScript. Features a masonry grid layout, interactive lightbox with multi-control zoom, category and live text filtering, favoriting system, and mobile touch gestures.

---

## ✨ Features

- **Responsive Masonry Grid:** Dynamically adjusts across viewports (1 column on mobile, up to 4 columns on large displays).
- **Lightbox Modal:**
  - Previous / Next navigation with wraparound looping.
  - Interactive zoom controls (Zoom In, Zoom Out, Reset).
  - Collapsible slide-over metadata drawer (photographer, location, EXIF/camera details, tags).
  - Background click-to-close and smooth fade transitions.
- **Keyboard Shortcuts & Gestures:**
  - `←` / `→`: Navigate photos.
  - `Esc`: Close lightbox.
  - `+` / `-`: Zoom in / Zoom out.
  - `Space`: Toggle metadata side drawer.
  - Mobile swipe left/right to navigate images.
- **Search & Filtering:**
  - Real-time text search across title, location, photographer, and tags.
  - Category pill tabs with dynamic count badges.
  - Personal favorites toggle with badge counter.
  - Empty state fallback with one-click reset.

---

## 📁 File Structure

```text
├── index.html        # Complete standalone application (HTML, CSS, JS)
└── README.md         # Project documentation
```

---

## 🚀 Getting Started

No build tools, bundlers, or package installations are required.

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser:
   ```bash
   # On macOS
   open index.html

   # On Linux
   xdg-open index.html

   # On Windows
   start index.html
   ```
3. Alternatively, serve it via a lightweight local server:
   ```bash
   npx serve .
   # or
   python3 -m http.server 8000
   ```

---

## 🛠️ Built With

- **HTML5** & **Vanilla JavaScript (ES6+)**
- **[Tailwind CSS (CDN)](https://tailwindcss.com/)** for styling and animations
- **[Lucide Icons](https://lucide.dev/)** for UI iconography
- **[Inter Font](https://fonts.google.com/specimen/Inter)** via Google Fonts
- Image assets curated via **[Unsplash](https://unsplash.com/)**

---

## ⌨️ Keyboard Shortcuts (Lightbox Mode)

| Key | Action |
| --- | --- |
| `←` (Left Arrow) | View previous photo |
| `→` (Right Arrow) | View next photo |
| `Esc` | Close lightbox |
| `Space` | Toggle photo metadata panel |
| `+` / `=` | Zoom in (up to 3x) |
| `-` | Zoom out (down to 0.75x) |

---

## 📄 License

This project is open-source and free to use for personal or commercial projects. Sourced photography is subject to the [Unsplash License](https://unsplash.com/license).