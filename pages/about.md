---
title: About
slug: about
---

/\* Unified Stacked Layout (Mobile Portrait, Tablet Portrait, Narrow Desktop) \*/ /\* Forces the stack at 800px to prevent cramped text, and immediately left-aligns \*/ @media (max-width: 800px) { .hero-container { margin-top: 0px; } .hero-photo-col { flex: 1 1 100% !important; /\* Forces the layout to wrap \*/ max-width: 350px !important; margin-right: auto !important; /\* Keeps it left-aligned immediately upon stacking \*/ } } /\* Tablet layout (Landscape): target touch devices specifically to protect desktop layout \*/ @media (min-width: 951px) and (hover: none) and (pointer: coarse) { .hero-container { margin-top: 0px; } } /\* Mobile layout (Landscape): Asymmetrical side-by-side to keep CTA above the fold \*/ @media (max-height: 600px) and (orientation: landscape) and (hover: none) and (pointer: coarse) { .gh-head, .gh-head-inner, .site-header { padding-top: 5px !important; margin-top: 0 !important; } .site-wrapper { padding-top: 0 !important; margin-top: 0 !important; } .hero-container { margin-top: -65px !important; flex-wrap: nowrap !important; gap: 32px !important; } .hero-photo-col { flex: 0 0 280px !important; max-width: 280px !important; margin-right: 0 !important; } .hero-text-col { flex: 1 1 auto !important; max-width: 100% !important; } .hero-title { font-size: 26px !important; margin-bottom: 16px !important; } .hero-link { font-size: 22px !important; } } /\* Desktop layout (Side-by-side): Optical alignment adjustment \*/ @media (min-width: 900px) { .hero-text-col { margin-top: -10px; } }

![](https://storage.ghost.io/c/86/cd/86cd0066-a957-488f-b0e4-a5bc82f2723d/content/images/size/w1600/2026/05/IMG_20190619_122911--2-.jpg)

Hello, I'm Derrick Farnell. I'm an independent researcher and a writer, mainly interested in how the mind works. I live in Edinburgh, Scotland.
-----------------------------------------------------------------------------------------------------------------------------------------------

### [Read my articles →](https://www.derrickfarnell.site/articles/)