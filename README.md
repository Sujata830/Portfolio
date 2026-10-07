# Academic Portfolio Website — Bachelor of Information Technology (BIT)

**Student Name:** Sujata Woad  
**Program:** Bachelor of Information Technology (BIT) — 2nd Year (Section R)  
**Institution:** MIT College, Nepal  
**Repository:** [https://github.com/Sujata830/Portfolio](https://github.com/Sujata830/Portfolio)  
**Live Website:** [https://sujata830.github.io/Portfolio/](https://sujata830.github.io/Portfolio/)  

---

## 1. Assignment Overview & Objectives

This academic portfolio expands upon the initial semantic HTML5 foundation by implementing custom CSS3 styling, modern responsive layout modules, and deployment through GitHub Pages.

### Core Academic Competencies Demonstrated:
- **Strict Separation of Concerns:** Complete architectural decoupling of document content/semantics (`index.html`) from visual presentation (`style.css`), with zero inline styles (`style=""`) and zero internal `<style>` tags.
- **Modern CSS Layout Architecture:** Extensive, intentional utilization of **Flexbox** (for navigation, headers, component alignment, button clusters, and footer) and **CSS Grid** (for multi-column hero layouts, skill category matrices, and project card arrangements).
- **Responsive Web Design:** Fluid typography (`clamp()`), fluid dimensions, and purposeful media queries supporting desktop (1440px+), standard laptops (1024px), tablets (768px), and mobile devices (480px, 360px) without horizontal scrolling or layout degradation.
- **Web Accessibility (WCAG 2.1 AA):** High-contrast color combinations, dedicated `:focus-visible` keyboard focus indicators, landmark navigation (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`), and accessible skip links (`#main-content`).
- **Static Deployment & Git Workflow:** Standard static file structure using relative pathing suitable for direct publication on GitHub Pages.

---

## 2. Project Architecture & File Structure

```text
portfolio/
├── index.html            # Semantic HTML5 document (markup and accessibility structure)
├── style.css             # External CSS3 stylesheet (design system, layouts, media queries)
├── README.md             # Academic project documentation
└── images/               # Asset directory
    ├── profile.png       # Authentic student profile photograph
    ├── image 4.png       # Profile photograph original source
    ├── project-portfolio.svg    # Vector mockup for Portfolio Website project
    ├── project-database.svg     # Vector architecture for Student Database project
    └── project-networking.svg   # Vector diagram for Networking Quiz App project
```

---

## 3. Design System & CSS Architecture

`style.css` is structured into 13 distinct logical modules:

1. **CSS Variables / Design System (`:root`):**
   - Cohesive slate-and-blue academic palette (`--color-primary`, `--color-secondary`, `--color-bg`, `--color-surface`, `--color-text`, `--color-border`).
   - Standardized typography scale (`--font-sans`, `--font-mono`, `--font-size-*`).
   - 8-point geometric spacing system (`--space-2xs` to `--space-3xl`).
   - Consistent border radii and multi-layered elevation shadows (`--shadow-sm` to `--shadow-hover`).
2. **Reset / Base Styles:** Universal box-sizing (`box-sizing: border-box`), image resets, and scroll offsets (`scroll-margin-top: 85px`) to prevent sticky navbar occlusion.
3. **Global Typography & Utilities:** Fluid headings, container constraints (`max-width: 1140px`), and reusable button component variants (`.btn-primary`, `.btn-secondary`, `.btn-outline`).
4. **Header & Navigation:** Sticky header with backdrop blur and Flexbox navigation bar.
5. **Hero Section:** Two-column responsive CSS Grid pairing an authentic student bio with an elevated profile card and academic badge.
6. **About Section:** Two-column CSS Grid detailing university background, academic degree details, and core software engineering principles.
7. **Skills Section:** Auto-fitting CSS Grid displaying four categories (Web Development, Programming Languages, Database Management, Tools & Systems) with pill-shaped skill tags.
8. **Projects Section:** CSS Grid of semantic `<article>` cards featuring vector thumbnail previews, tech stack badges, and GitHub repository links.
9. **Contact Section:** Dual-panel layout featuring verified student contact details (`sujatawoad8@gmail.com`, GitHub) and an accessible contact form with form validation states.
10. **Footer:** Responsive Flexbox footer containing university credentials, navigation links, copyright notice, and a "Back to Top" anchor.
11. **Hover, Focus & Accessibility States:** High-contrast focus outlines and `@media (prefers-reduced-motion: reduce)` support.
12. **Responsive Media Queries:** Intentional layout transformations at 1024px, 768px, 480px, and 360px breakpoints.

---

## 4. Git & GitHub Pages Deployment Guide

To deploy this project to GitHub Pages:

1. **Stage all changes:**
   ```bash
   git add index.html style.css README.md images/
   ```
2. **Commit with a descriptive message:**
   ```bash
   git commit -m "Implement responsive CSS3 design system and semantic portfolio layout"
   ```
3. **Push to the main branch:**
   ```bash
   git push origin main
   ```
4. **Enable GitHub Pages:**
   - Navigate to the repository on GitHub: `https://github.com/Sujata830/Portfolio`
   - Click on **Settings** &rarr; **Pages** (left sidebar).
   - Under **Build and deployment** &rarr; **Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and root directory `/(root)`.
   - Click **Save**.
   - The site will be live at `https://sujata830.github.io/Portfolio/` within 1–2 minutes.

---

## 5. Academic Integrity Statement

All personal, institutional, and project information contained within this repository represents genuine coursework for Sujata Woad, 2nd Year BIT student at MIT College, Nepal. No employment, commercial awards, or false professional experiences have been fabricated.
