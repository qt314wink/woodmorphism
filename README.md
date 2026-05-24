# 🪵 Woodmorphism

> A warm, organic design system rooted in natural material aesthetics — wood grain textures, earthy tones, and tactile depth.

![Design System](https://img.shields.io/badge/design--system-woodmorphism-8B5E3C?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-in%20development-yellow?style=flat-square)

---

## ✨ Concept

Woodmorphism is a UI design language inspired by the warmth and texture of natural wood. It blends soft shadows, grain-like surface patterns, and an earthy palette to create interfaces that feel grounded, tactile, and alive — the antidote to sterile flat design.

It lives in the same material-morphism family as neumorphism and glassmorphism, but draws its energy from the organic world rather than synthetic surfaces.

---

## 🎨 Design Tokens

| Token | Value | Description |
|---|---|---|
| `--wood-base` | `#C8A97E` | Primary warm wood tone |
| `--wood-dark` | `#6B3F1E` | Deep walnut shadow |
| `--wood-light` | `#F0DFC0` | Pale birch highlight |
| `--wood-grain` | SVG noise filter | Subtle grain texture overlay |
| `--wood-radius` | `12px` | Rounded corners, natural feel |
| `--wood-shadow` | `4px 4px 12px rgba(80,40,10,0.3)` | Warm directional shadow |

---

## 🧩 Components (Planned)

- `WoodCard` — Elevated surface with grain texture
- `WoodButton` — Tactile press-state buttons
- `WoodInput` — Form fields with inset-wood feel
- `WoodBadge` — Carved label elements
- `WoodDivider` — Bark-ring separator

---

## 🚀 Usage

This repo serves as a design token reference and component spec. Implementation targets HTML/CSS and React.

```css
/* Import core tokens */
@import url('./tokens/woodmorphism.css');

.wood-card {
  background: var(--wood-light);
  border-radius: var(--wood-radius);
  box-shadow: var(--wood-shadow);
}
```

---

## 🔗 Related Projects

- [Neumorphism Soft UI Design System](https://github.com/qt314wink/neumorphism-soft-ui-design-system) — Jewelmorphism & physics animations
- [Chromaflora](https://github.com/qt314wink/chromaflora-sitezip) — Color-forward floral UI system
- [Design Standards 2026–2027](https://github.com/qt314wink/design-standards-2026-2027) — Cross-system design guidelines

---

## 📄 License

MIT © [Jennipher Troup](https://github.com/qt314wink)
