# 🪐 TheRealArchitect Portfolio

> A high-performance, dark-crimson themed portfolio showcasing browser-based operating systems, AI implementations, and web utilities. Built with modern CSS custom properties, smooth horizontal snap-scrolling, and interactive elements.
> 
---

## 🛠️ Project Showcase

This repository orchestrates a custom horizontal stage featuring several prominent web creations:

| Project | Description | Role / Status |
| :--- | :--- | :--- |
| **Win12 Online** | A full Windows 12 experience running entirely in the browser. | 3rd Party Contributor |
| **Cipher Linux** | A custom web-based Linux environment showcase. | Creator / Owner |
| **Architect AI** | A specialized Gemini Gem acting as an AI twin of the architect. | Creator / Owner |
| **Boredom Eraser** | An interactive hub designed to slash boredom with web experiments. | Creator / Owner |
---

## 📦 Technical Specifications & Architecture

### Frontend Tech Stack
* **Structure:** Semantic HTML5
* **Styling:** Native CSS3 with custom variables (`:root`), absolute fixed layouts, and desktop fluid sizing (`clamp()`).
* **Typography:** Google Fonts integration (`Bebas Neue` & `Space Mono`).
* **Iconographies Installed:** * Lucide Icons (Static Font integration)
* Phosphor Icons (Web Font integration)

### Key Features
* **Dynamic View Port Switching:** Custom JavaScript handlers manage hardware-accelerated transitions (`opacity` and `translateY`) between the landing Hero stage and the main dashboard.
* **Smart Scroll Translation:** Intercepts traditional vertical scroll-wheel deltas (`wheel` event listeners) to drive multi-directional UX, turning vertical mouse tracking into fluid horizontal track scrolling.
* **Responsive Gesture Mapping:** Touch tracking algorithms compute Y-axis displacement handles (`touchstart`/`touchend`) to trigger interface shifts smoothly on mobile environments.

---

## 🎨 Asset Tree Setup

To ensure all visual components load correctly, preserve the following directory layout:

```text
├── assets/
│   ├── main.png            # Main branding icon / Favicon
│   ├── win12.png           # Windows 12 Card Thumbnail
│   └── button.png          # Boredom Eraser Graphic
├── css/
│   └── extras.css          # Auxiliary layout modifiers
├── index.html              # Core architecture deployment file
└── README.md               # Repository documentation
