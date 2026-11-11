# Low-Demand Sensory Accessibility Specification (ADS V2.1)

An open architectural standard for neurodivergent-accessible digital interfaces, low-arousal contrast palettes, and non-flicker state transitions.

Published by VagusHQ · [https://www.vagushq.com](https://www.vagushq.com)

---

## 1. Principles of Sensory-Safe Computing

Traditional web interfaces frequently rely on high-frequency animations, stark saturated pure-white canvases (`#FFFFFF`), aggressive notifications, and high cognitive-demand menus. For neurodivergent users experiencing executive fatigue, sensory gating sensitivity, or demand fatigue, these patterns contribute to acute cognitive drain.

The Autonomic Design Standard (ADS V2.1) provides three foundational rules:

1. **Low-Arousal Warm Canvases:** Eliminate pure `#FFFFFF` backgrounds and pure `#000000` text to prevent visual glare and retinal exhaustion.
2. **Predictable Linear Layouts:** Maintain strict spatial predictability. Avoid dynamic layout shifts, sudden popovers, or countdown timers.
3. **Paced Visual Grounding:** Provide gentle, user-paced rhythms rather than high-frequency infinite feeds.

---

## 2. Canonical Color Token Architecture

The palette utilizes warm, muted natural tones with high legibility across both screen devices and print media:

```css
:root {
  /* Screen & Ink Canvases */
  --canvas-silk: #F9F8F6;       /* Primary screen background */
  --canvas-warm-stone: #F4F1EA; /* Secondary container background */
  --canvas-print: #FDFCFB;      /* Ink-saver print background */

  /* Structural Typography & Ink */
  --ink-slate: #2C3E50;         /* Primary high-contrast body text */
  --ink-sage: #6F8065;          /* Secondary descriptive text & accents */
  --ink-azure: #A1B5D8;         /* Calming informational highlights */
  --accent-ember: #C05A2E;      /* Focused calls-to-action (max 10% area) */
}
```

---

## 3. Reference Implementation & Resources

* **Live Interactive Web Pacer:** [Vagus Focus Pacer](https://wcb0alpha.github.io/VagusHQ-Open-Research/)
* **Canonical Knowledge Hub:** [VagusHQ](https://www.vagushq.com)
* **Assessment Framework:** [VagusHQ Pathways](https://pathways.vagushq.com)
