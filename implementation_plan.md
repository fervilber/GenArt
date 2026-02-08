# Implementation Plan - Algorithmic Art Website

## Goal Description

Create a modern, dynamic website for algorithmic art using p5.js. The site will feature a landing page and three distinct art pieces: "Falling Circles", "Cosmic Orbits", and "Flow Fields".
**Update**: The main landing page (`index.html`) will itself be an interactive algorithmic art piece ("The Void") featuring a dynamic background and "slices" (sliders) for real-time parameter manipulation, creating an immediate "wow" effect.

## User Review Required

> [!IMPORTANT]
> **External Dependency**: This plan requires `p5.js`. I will use a CDN link (cdnjs) for development. If offline access is required, please download `p5.min.js` to a `lib/` folder.

## Proposed Changes

### Documentation

#### [NEW] [ALGORITHMIC_PHILOSOPHY.md](file:///d:/PROYECTOS/PROGRMAS/2026/GenArt/ALGORITHMIC_PHILOSOPHY.md)

- Define the "Organic Complexity" philosophy (Already created).

### Web Structure

#### [MODIFY] [index.html](file:///d:/PROYECTOS/PROGRMAS/2026/GenArt/index.html)

- **Concept**: "The Void" - A dark, immersive landing page with a subtle, interactive particle system.
- **Tech**: Embed p5.js directly.
- **Features**:
  - Full-screen canvas background.
  - Floating glass-morphism cards for the 3 art pieces.
  - **Control Panel**: A sleek "Slices" UI to tweak "Chaos", "Speed", and "Density" of the background.
  - Minimalist, premium typography (Poppins/Lora).

### Art Pieces (To be implemented in future steps)

#### [NEW] [art/falling_circles.html](file:///d:/PROYECTOS/PROGRMAS/2026/GenArt/art/falling_circles.html)

- Interactive p5.js sketch of circles dropping.

#### [NEW] [art/cosmic_orbits.html](file:///d:/PROYECTOS/PROGRMAS/2026/GenArt/art/cosmic_orbits.html)

- N-body simulation.

#### [NEW] [art/flow_fields.html](file:///d:/PROYECTOS/PROGRMAS/2026/GenArt/art/flow_fields.html)

- Perlin noise flow fields.

## Verification Plan

### Automated Tests

- None currently (visual project).

### Manual Verification

1. **Main Page Interactivity**:
   - Open `index.html`.
   - Move mouse: Background particles should react (repel/attract).
   - Adjust Sliders: "Chaos" should increase jitter, "Speed" should change movement rate.
2. **Responsiveness**:
   - Resize window: Canvas should resize dynamically. Cards should stack on mobile.
3. **Navigation**:
   - Click art cards: Should navigate to placeholder/404 pages (until art pieces are built).
