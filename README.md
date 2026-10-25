# mannorr.com

Homepage for MANNORR — Adeniran Oluwanifemi, Creative Director & Visual Designer.

A single static page (`index.html`). No build step: open it in a browser or upload it to any static host.
Motion runs on GSAP + ScrollTrigger, loaded from cdnjs. Fonts are Instrument Serif, DM Mono and Syne from Google Fonts.

## Adding images

Every image slot shows a labelled placeholder until its file exists. Drop files in with these exact names:

| File | Where it appears |
|---|---|
| `hero.png` (site root) | Hero portrait — transparent cut-out, side profile works best |
| `images/service-01.jpg` … `service-08.jpg` | Services grid, in this order: Brand Identity Systems, Campaign Development, UI/UX Design & Prototyping, Creative Direction, Logo Design & Visual Identity, Typography & Editorial Layout, Social Media Visual Strategy, Design Systems & Frameworks |
| `images/work-01.jpg` … `work-04.jpg` | Selected Works full-screen backgrounds |
| `images/work-01-cover.jpg` … `work-04-cover.jpg` | Small centre card on each project (3:4) |
| `images/showreel.mp4` | Showreel — muted, looping |
| `images/portrait-close.jpg` | Closing section portrait (4:5) |

Project titles, years, disciplines and clients are marked `[like this]` in `index.html`.

## Before launch

- The contact form is a front-end only. Connect it to a form service (Formspree, Netlify Forms, etc.) — search for `contactForm` in `index.html`.
- "View All Works", "Full Story + Brand Guide" and "Download CV" link to the existing `portfolio.html`, `about.html` and CV on mannorr.com. Keep those files on the host.

## Theme

Light mode uses red (`#E4291C`), dark mode uses volt (`#C8FF00`). The sun button in the nav switches between them; the visitor's system setting is the default.
