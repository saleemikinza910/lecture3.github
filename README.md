lecture3.github

 Kinza Saleemi · Manual Layout Switcher + 3‑Phone Demo

A responsive portfolio-style demo that showcases a manual layout override system for navigation bars, along with an interactive 3‑phone gallery that illustrates consistent stacking behavior on mobile devices.
Built with pure HTML, CSS, and JavaScript – no external libraries.

HTML5 CSS3 JavaScript

🚀 Live Demo

Click here to see the live demo
(Replace with your actual deployment URL, e.g., Netlify / Vercel / GitHub Pages)

✨ Features

Responsive Navigation Bar
– stacks vertically on mobile (<768px)
– side‑by‑side on desktop (≥768px) using modern flexbox.

Manual Layout Override
Cycle through three layout modes with one floating button:
Auto – default responsive behaviour (CSS media query)
Force Stack – force vertical navigation even on wide screens
Force Row – force horizontal navigation even on narrow screens
3‑Phone Showcase
– hidden by default, revealed only when the user clicks “Show 3‑Phone Demo”.
– Three simulated phone frames (320px, 375px, 428px) each with a mini profile & stacked navbar.
– Demonstrates how the navbar always stacks in a mobile context.

Modern UI Design
– Glassmorphism profile card, animated gradient text, custom stats badges, and floating action buttons.
– Realistic avatar via randomuser.me (with a text fallback).

Fully Responsive & Touch‑Friendly
– Works on any device, from iPhone SE to 4K monitors.
🛠️ Technologies Used

Technology	Purpose
HTML5	Page structure, semantic elements
CSS3	Flexbox, custom properties, backdrop‑filter, media queries, gradient text
Vanilla JavaScript	Manual layout cycling, phone showcase toggling, DOM manipulation
No frameworks, no build step – just open index.html and enjoy.
