NeonX Gen‑2 — Futuristic UI
NeonX Gen‑2 is a modern HTML/CSS starter focused on a futuristic “8th‑gen” aesthetic: glassmorphism, neon accents, gooey morphing blobs, 3D tilt, magnetic buttons, and smooth scroll reveals. It’s built with accessible, lightweight patterns and CSS variables for instant theming.

Features:-
 Glass UI surfaces with backdrop blur and soft borders.
 Neon glow typography and accent CTAs.
 Gooey blob background using SVG filters (lava‑lamp style).
 3D tilt on cards using perspective and transforms.
 Magnetic buttons that subtly follow the cursor.
 Scroll reveal animations via IntersectionObserver.
 One‑click dark/light theme toggle using data attributes and CSS variables.
 Reduced‑motion friendly defaults.
 
 Project structure:-
  index.html: Page markup, SVG filters, canvas grid, interactions (tilt, magnetic, reveal, theme toggle).
  styles-gen2.css: Theme tokens, glass surfaces, blobs, panels, buttons, responsive rules.

Getting started:-
 Download index.html and styles-gen2.css into the same folder.
 Open index.html in a modern browser.
 Optional: Serve locally (any static server) for best performance with fonts.
 Customize theme in styles-gen2.css by editing CSS variables in :root and :root[data-theme="light"].

 Theming:-
   Edit color tokens: --primary, --accent, --lime, --text, --muted, --bg.
   Adjust depth: --blur, --shadow, --radius.
   Switch modes by toggling data-theme="dark" | "light" on the html element (already wired to a button).

Accessibility:-
  Motion: Respects prefers-reduced-motion; keep blob animation durations higher for calmer motion.
  Contrast: Ensure text over glass/gradients maintains accessible contrast.
  Focus: Form inputs and interactive controls have visible focus rings.

Performance tips:-
  Blur and heavy filters are GPU‑intensive. Use them sparingly, especially on mobile.
  Keep stdDeviation (SVG blur) modest.
   Limit simultaneous animated elements; stagger where possible.
   Prefer variable fonts or system stacks to reduce font payload.

Customization guide:-
  Replace hero heading/subtitle and CTA labels.
  Tweak blob sizes/positions and animation timing for different moods.
  Adjust 3D tilt sensitivity (degrees and translateZ).
  Tune magnetic strength (pixels divisor) for buttons.
   Modify the canvas grid size and color for different ambience.

Roadmap (future updates):-
