# Woodmorphism Design System

**Creator:** Jennipher Troup · [girlwithstarryeyes@outlook.com](mailto:girlwithstarryeyes@outlook.com)

> *Part of the **Morphica** family — a series of design systems that translate physical material properties and natural phenomena into browser-native UI language.*

A design system derived from wood: grain direction, growth ring layering, structural honesty. Woodmorphism is the anti-digital design system — it borrows nothing from glass, metal, or synthetic material. Every rule in the system can be justified by asking: *does wood do this?*

---

## Design Principles

**Grain direction is hierarchy.** In wood, the grain tells you where the strength runs. In Woodmorphism, typographic flow, layout direction, and reading order follow the same logic: the dominant axis is the grain, secondary content runs perpendicular.

**Growth rings are depth.** Real wood depth comes from annual growth rings — concentric, warm, each a record of a season. Woodmorphism creates UI depth not through shadows and blurs but through layered warm tones, each ring slightly darker than the last, reading inward as increasing specificity.

**Structural honesty.** Wood shows its joints. Woodmorphism shows its structure: spacing is never hidden, component boundaries are visible rather than dissolved, interactive affordances are physical rather than implied. A button looks like something you could press with your thumb.

**Warmth is earned.** The warmth of wood comes from the material itself — it isn't applied, it's inherent. Woodmorphism's warmth lives in the token layer, not in decorative overlays.

---

## Design Tokens

```css
/* Grain palette — five warmth registers */
--wood-light:    #f5e6d0;   /* birch / maple highlight */
--wood-mid:      #c8956c;   /* oak surface */
--wood-deep:     #8b5e3c;   /* walnut core */
--wood-dark:     #4a2c17;   /* ebony shadow */
--wood-grain:    #a0714f;   /* grain line accent */

/* Ring depth — layered tonal system */
--ring-1:  rgba(200, 149, 108, 0.08);   /* outermost / lightest */
--ring-2:  rgba(200, 149, 108, 0.15);
--ring-3:  rgba(139,  94,  60, 0.22);
--ring-4:  rgba(139,  94,  60, 0.32);   /* innermost / darkest */

/* Structural shadow — single source, warm */
--shadow-grain:  2px 4px 12px rgba(74, 44, 23, 0.25);
--shadow-joint:  0 1px 0 rgba(74, 44, 23, 0.4);

/* Motion — organic, never snappy */
--t-settle:  0.35s cubic-bezier(0.25, 0.46, 0.45, 0.94);
--t-expand:  0.5s  cubic-bezier(0.22, 1, 0.36, 1);
```

---

## Naming Conventions

Woodmorphism tokens and components are named after wood species, structural terms, or fabrication techniques:

| Token / Component | Named After |
|---|---|
| `--wood-light` | Birch / Maple surface tone |
| `--wood-deep` | Walnut heartwood |
| `--ring-*` | Annual growth rings |
| `--shadow-joint` | Visible wood joint |
| `.plank` | Base card/surface component |
| `.mortise` | Inset / recessed container |
| `.tenon` | Protruding element / badge |
| `.kerf` | Divider / ruled line |

---

## Component Architecture

```
woodmorphism/
├── tokens/
│   ├── grain.css         # Wood palette + warmth registers
│   ├── rings.css         # Depth layering system
│   ├── motion.css        # Organic timing functions
│   └── structure.css     # Joint, shadow, grid
├── components/
│   ├── plank/            # Surface / card
│   ├── mortise/          # Inset container
│   ├── tenon/            # Badge / protrusion
│   ├── kerf/             # Divider
│   └── button/           # Structural press affordance
└── index.html            # Full component showcase
```

---

## The Morphica Family

| System | Material Source | Aesthetic |
|---|---|---|
| [ChromaFlora](https://github.com/qt314wink/chromaflora-sitezip) | Bioluminescence, cosmic growth | Procedural glow, living light, bloom |
| [Jewelmorphism](https://github.com/qt314wink/neumorphism-soft-ui-design-system) | Gems, crystal, refracted light | Chromatic depth, physics interaction |
| **Woodmorphism** | Wood grain, organic structure | Warmth, grain flow, structural honesty |

---

## Potential Morphica Expansions

The Morphica system is designed to grow. Each new member derives its entire token and naming vocabulary from a single physical material. Strong candidates:

| System | Material | Signal |
|---|---|---|
| Stonemorphism | Basalt, granite, slate | Weight, permanence, geological time |
| Papermorphism | Folded paper, origami | Layering, crease logic, flat-to-form |
| Fabricmorphism | Woven textile | Warp/weft grid, thread density, drape |
| Glassmorphism (true) | Blown glass, not frosted UI | Curvature, translucency, heat memory |
| Terramorphism | Fired clay, ceramic glaze | Porosity, glaze pooling, kiln marks |

---

girlwithstarryeyes@outlook.com · Philadelphia, PA
