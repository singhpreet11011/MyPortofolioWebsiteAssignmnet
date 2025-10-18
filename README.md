# MyPortofolioWebsiteAssignmnet
Link to my website: https://arshpreet-portofolio.netlify.app

Project Summary
A pixel-faithful, mobile-first portfolio built from the provided Figma templates. It includes Home, About, Tech Stack, Projects, and Contact sections and is available as a single scrolling page. The site uses semantic HTML, modern CSS (Flexbox/Grid), CSS variables for theming, Google Fonts (Poppins), and a Dark/Light mode toggle (preference saved in localStorage). Navigation supports smooth anchor scrolling on the one-pager and a compact mobile dropdown menu.
What’s included
Hero with gradient avatar ring and large typographic scale
About with work experience & education cards
Tech Stack icon grid (responsive)
Projects grid with cards (cover, summary, tech, actions)
Contact section with prominent email line
Shared header/footer and consistent spacing tokens
Strengths
Design fidelity: Spacing, typography, colors, and icon sizing closely match Figma.
Responsive by design: Mobile-first; grids adapt (icons 2→5 cols, projects 1→2→3).
Maintainable styles: Centralized CSS variables; minimal, readable class names.
Accessibility-minded: Semantic landmarks, labeled controls, keyboard-operable menus, adequate contrast in both themes.
Performance: No frameworks, tiny JS footprint, SVG icons; fast to load and easy to host.
Theme support: Dark/Light tokens consistently applied to panels, text, borders, and shadows.
Possible Weaknesses / Trade-offs
No build pipeline: Pure HTML/CSS/JS—simple to deploy, but lacks bundling/minification or PostCSS autoprefixing.
Limited interactivity: Intentional minimal JS; advanced behaviors (filters, search, animations) would benefit from a component setup.
Accessibility depth: Baseline A11y is covered; future work could add focus trapping for menus, reduced-motion variants, and broader keyboard testing.
Placeholder assets: Replace demo thumbnails/avatar with optimized images (.webp) for best quality and performance.
Testing & CI: Manual cross-browser checks only; no automated tests or Lighthouse CI yet.
