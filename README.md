# holbertonschool-web_front_end front
# HTML Advanced - Techium Project

## Description
This project focuses on learning how to structure a web page using HTML5 semantic tags.
No CSS or styling is used — the goal is to understand the structure and semantics of HTML.
The company used throughout this project is **Techium**.

---

## Learning Objectives
By the end of this project, you should be able to explain:
- Which guidelines to follow for HTML
- How to create the skeleton of an HTML5 page
- How to use semantic HTML tags to structure a web page
- Which use cases to use `div` vs `span`
- The semantic value of `header`, `main`, `footer`, `article`, `nav`, `section`, `aside`
- How to use headings and why hierarchical order is important
- How to make lists in HTML
- The differences between medias (SVG, GIF, PNG, JPG)
- How to structure data in a table
- How to integrate a video in a webpage
- How to integrate an audio file in a webpage
- How to embed external content
- How to correctly structure an HTML page

---

## Requirements
- All files should end with a new line
- Code is W3C compliant and validated with [W3C Validator](https://validator.w3.org/)
- No CSS or styling used

---

## Files

| File | Description |
|---|---|
| `0-index.html` | Basic HTML page with doctype and html tag |
| `1-index.html` | Add head and body structure |
| `2-index.html` | Add meta tags, title, description and favicons |
| `3-index.html` | Add header, main and footer |
| `article.html` | Add aside to article page |
| `5-index.html` | Add 7 sections to main |
| `6-index.html` | Add articles to works, news and testimonials |
| `7-index.html` | Add nav tag inside header |
| `8-index.html` | Add h1 heading to main |
| `9-index.html` | Add h2 headings to all sections |
| `10-index.html` | Add h3 headings to services, works, about and news |
| `11-styleguide.html` | Styleguide with all heading levels |
| `12-index.html` | Add paragraphs to sections |
| `13-styleguide.html` | Add paragraph section to styleguide |
| `14-index.html` | Add Techium span in header |
| `15-index.html` | Wrap content with div tags |
| `16-index.html` | Add header and div structure to sections |
| `17-index.html` | Add comments for code readability |
| `18-index.html` | Wrap span with link and div in header |
| `about.html` | About page |
| `latest_news.html` | Latest news page |
| `contact.html` | Contact page |
| `20-index.html` | Add navigation links to nav |
| `21-index.html` | Add social media links to footer |
| `22-index.html` | Add links to hero, about and contact sections |
| `23-index.html` | Add links inside h3 headings |
| `24-index.html` | Wrap nav and footer links in unordered lists |
| `25-index.html` | Add legal links to footer |
| `26-styleguide.html` | Add lists examples to styleguide |
| `27-index.html` | Add horizontal rule and copyright to footer |
| `28-styleguide.html` | Add horizontal rule section to styleguide |
| `29-index.html` | Add blockquotes to testimonials |
| `30-styleguide.html` | Add blockquotes section to styleguide |
| `31-index.html` | Add address to footer and authors to news |
| `32-styleguide.html` | Add typography section to styleguide |
| `33-styleguide.html` | Add table section to styleguide |
| `34-styleguide.html` | Add details section to styleguide |
| `35-index.html` | Add logo image to header and footer |
| `index.html` | Final index page with SVG icons |
| `38-styleguide.html` | Add video section to styleguide |
| `39-styleguide.html` | Add audio section to styleguide |
| `styleguide.html` | Final styleguide with iframe section |

---

## HTML Guidelines
- Always use **lowercase** for tags and attributes
- Always **close** your tags
- Always use **quotes** around attribute values
- Use the `<!DOCTYPE html>` declaration at the top
- Validate your code with the **W3C Validator**
- Use **UTF-8** encoding
- Only **one `<h1>`** per page
- Always respect heading order: `h1 → h2 → h3`

---

## Semantic Tags Used

| Tag | Role |
|---|---|
| `<header>` | Top of the page / logo / nav |
| `<main>` | Main content of the page |
| `<footer>` | Bottom of the page |
| `<nav>` | Navigation links |
| `<section>` | Group of related content |
| `<article>` | Independent content |
| `<aside>` | Secondary content |
| `<div>` | Generic block container |
| `<span>` | Generic inline container |

---

## Media Types

| Format | Transparency | Animation | Best for |
|---|---|---|---|
| **JPG** | ❌ | ❌ | Photos |
| **PNG** | ✅ | ❌ | Images with transparency |
| **GIF** | ✅ | ✅ | Simple animations |
| **SVG** | ✅ | ✅ | Icons, logos (vector) |

---

## Resources
- [HTML 5.2](https://www.w3.org/TR/html52/)
- [HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [HTML Reference](https://htmlreference.io/)
- [Can I use](https://caniuse.com/)
- [HTML Cheat Sheet](https://websitesetup.org/html5-cheat-sheet/)

---

# 📚 Guide Complet CSS Advanced — Projet Techium

---

## 🏗️ Structure du projet

```
CSS_advanced/
├── index.html          ← fichier HTML fourni
├── styles/
│   ├── 1-style.css     ← smooth scrolling
│   ├── 2-style.css     ← couleurs
│   ├── 3-style.css     ← variables CSS
│   ├── 4-style.css     ← variables fonts
│   ├── 5-style.css     ← variables font-size
│   ├── 6-style.css     ← variables font-weight
│   ├── 7-style.css     ← web fonts
│   ├── 8-style.css     ← variables line-height
│   ├── 9-style.css     ← text-decoration
│   ├── 10-style.css    ← section-header
│   ├── 11-style.css    ← section-tagline
│   ├── 12-style.css    ← section-title
│   ├── 13-style.css    ← pseudo-classes
│   ├── 14-style.css    ← normalize.css
│   ├── 15-style.css    ← box-sizing
│   ├── 16-style.css    ← container
│   ├── 17-style.css    ← padding sections
│   ├── 18-style.css    ← navbar
│   ├── 19-style.css    ← grid
│   ├── 20-style.css    ← clearfix
│   ├── 21-style.css    ← col- selector
│   ├── 22-style.css    ← dark theme
│   ├── 23-style.css    ← footer/social
│   ├── 24-style.css    ← services cards
│   ├── 25-style.css    ← buttons
│   ├── 26-style.css    ← testimonials
│   ├── 27-style.css    ← hero section
│   ├── 28-style.css    ← header
│   ├── 29-style.css    ← nav hover
│   ├── 30-style.css    ← works section
│   ├── 31-style.css    ← quotes decoration
│   └── 32-style.css    ← transitions
└── images/
    ├── favicon.jpg
    ├── logo-black.png
    ├── logo-white.png
    └── pic-*.jpg
```

---

## 📋 Toutes les variables CSS utilisées

```css
:root {
  /* ===== COULEURS ===== */
  --color-primary: #d73953;
  --color-black: #090909;
  --color-white: #ffffff;
  --color-light-grey: #f3f3f3;
  --color-dark-grey: #353535;
  --text-color: var(--color-black);

  /* ===== TYPOGRAPHIE ===== */
  --font-family-base: "Open Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  --font-family-title: Raleway, "Helvetica Neue", Helvetica, Arial, sans-serif;

  /* ===== TAILLES DE POLICE ===== */
  --font-size-small: 1.2rem;
  --font-size-medium: 1.6rem;
  --font-size-large: 1.8rem;
  --font-size-x-large: 2.3rem;
  --font-size-xx-large: 4.8rem;

  /* ===== POIDS DE POLICE ===== */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* ===== HAUTEUR DE LIGNE ===== */
  --line-height-small: 1.2;
  --line-height-base: 1.5;
  --line-height-big: 1.8;

  /* ===== SECTIONS ===== */
  --section-header-align: center;
  --section-tagline-transform: uppercase;
  --section-tagline-margin: 0;
  --section-title-margin: 0;
  --section-title-color: var(--color-black);
  --section-padding: 5rem 0;
  --section-header-padding: 0 0 3rem;
  --section-body-padding: 0 0 3rem;
  --section-footer-padding: 3rem 0 0;
  --section-footer-align: center;

  /* ===== FOOTER ===== */
  --footer-padding: 5rem 0 1rem;

  /* ===== NAVIGATION ===== */
  --nav-item-font-family: var(--font-family-title);
  --nav-item-font-weight: var(--font-weight-bold);
  --nav-item-font-size: var(--font-size-medium);
  --nav-item-letter-spacing: 0.04rem;
  --nav-item-display: inline-block;
  --nav-item-margin: 0 0 3rem 0;
  --nav-item-link-hover: var(--color-white);

  /* ===== BOUTONS ===== */
  --button-display: inline-block;
  --button-padding: 1.5rem 3rem;
  --button-border: 0.2rem solid var(--color-primary);
  --button-color: var(--color-black);
  --button-text-decoration: none;
  --button-font-size: var(--font-size-large);
  --button-hover-color: var(--color-white);
  --button-hover-text-decoration: none;
  --button-hover-background: var(--color-primary);

  /* ===== HEADER ===== */
  --header-padding: 4rem 0 0;
  --header-logo-position: relative;
  --header-logo-link-display: inline-block;
  --header-logo-link-position: absolute;
  --header-logo-link-top: -1rem;
  --header-logo-link-left: 0;

  /* ===== TRANSITIONS ===== */
  --transition-duration: .3s;
  --transition-cubic-bezier: cubic-bezier(0.17, 0.67, 0, 1.01);
}
```

---

## 🎨 Tâche 1 — Smooth Scrolling

```css
html {
  scroll-behavior: smooth;
}
```
> Rend le scroll fluide quand on clique sur un lien ancre

---

## 🎨 Tâche 2 — Couleurs de base

```css
body {
  color: #161616;
}

a {
  color: #161616;
}

.visually-hidden {
  display: none;
}

.card-category {
  color: #D73953;
}

.section-tagline {
  color: #D73953;
}
```

---

## 🎨 Tâche 3 — Variables CSS (Custom Properties)

```css
:root {
  --color-primary: #d73953;
  --color-black: #090909;
  --color-white: #ffffff;
  --color-light-grey: #f3f3f3;
  --color-dark-grey: #353535;
  --text-color: var(--color-black);
}

body {
  color: var(--text-color);        /* utilisation de variable */
}

.section-tagline {
  color: var(--color-primary);     /* utilisation de variable */
}
```

> **Pourquoi les variables ?** Modifier une couleur = changer 1 seule ligne !

---

## 🎨 Tâche 4 — Variables de polices

```css
:root {
  --font-family-base: "Open Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  --font-family-title: Raleway, "Helvetica Neue", Helvetica, Arial, sans-serif;
}

body {
  font-family: var(--font-family-base);
}

h1, h2, h3, h4, h5, h6 {
  font-family: var(--font-family-title);
}
```

---

## 🎨 Tâche 5 — Variables de tailles de police

```css
:root {
  --font-size-small: 1.2rem;
  --font-size-medium: 1.6rem;
  --font-size-large: 1.8rem;
  --font-size-x-large: 2.3rem;
  --font-size-xx-large: 4.8rem;
}

html {
  font-size: 62.5%; /* 1rem = 10px */
}

body {
  font-size: var(--font-size-medium); /* = 16px */
}
```

> **Astuce** : `font-size: 62.5%` sur `html` = `1rem = 10px`
> Donc `1.6rem = 16px`, `4.8rem = 48px`

---

## 🎨 Tâche 6 — Variables de poids de police

```css
:root {
  --font-weight-regular: 400;
  --font-weight-bold: 700;
}

body {
  font-weight: var(--font-weight-regular);
}

h1, h2, h3, h4, h5, h6 {
  font-weight: var(--font-weight-bold);
}
```

---

## 🎨 Tâche 7 — Polices web (Google Fonts)

```css
/* Dans le HTML */
/* <link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700|Raleway:700"> */

:root {
  /* Open Sans = première priorité pour le texte */
  --font-family-base: "Open Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;

  /* Raleway = première priorité pour les titres */
  --font-family-title: Raleway, "Helvetica Neue", Helvetica, Arial, sans-serif;
}
```

---

## 🎨 Tâche 8 — Variables de hauteur de ligne

```css
:root {
  --line-height-small: 1.2;
  --line-height-base: 1.5;
  --line-height-big: 1.8;
}

body {
  line-height: var(--line-height-base);
}
```

---

## 🎨 Tâche 9 — Supprimer la décoration des liens

```css
a:link {
  color: var(--text-color);
  text-decoration: none;    /* supprime le soulignement */
}
```

---

## 🎨 Tâche 10 — Alignement du header de section

```css
:root {
  --section-header-align: center;
}

.section-header {
  text-align: var(--section-header-align);
}
```

---

## 🎨 Tâche 11 — Style de la tagline de section

```css
:root {
  --section-tagline-transform: uppercase;
}

.section-tagline {
  color: var(--color-primary);
  font-family: var(--font-family-title);
  text-transform: var(--section-tagline-transform);
  font-weight: var(--font-weight-bold);
}
```

---

## 🎨 Tâche 12 — Style du titre de section

```css
:root {
  --section-title-margin: 0;
  --section-title-color: var(--color-black);
}

.section-title {
  font-family: var(--font-family-title);
  font-size: var(--font-size-xx-large);
  font-weight: var(--font-weight-bold);
  margin: var(--section-title-margin);
  color: var(--section-title-color);
}
```

---

## 🎨 Tâche 13 — Pseudo-classes des liens

```css
/* Lien normal */
a:link {
  color: var(--text-color);
  text-decoration: none;
}

/* Lien visité */
a:visited {
  font-style: italic;
}

/* Lien survolé */
a:hover {
  text-decoration: underline;
}

/* Lien cliqué */
a:active {
  background-color: var(--color-light-grey);
}
```

> **Ordre important** : toujours dans cet ordre LVHA !
> **L**ink → **V**isited → **H**over → **A**ctive

---

## 🎨 Tâche 14 — Normalize.css

```css
/*! normalize.css v8.0.1 | MIT License | github.com/necolas/normalize.css */
/* Coller le contenu complet de normalize.css ici */
```

> Normalise les styles par défaut de tous les navigateurs

---

## 🎨 Tâche 15 — Box-sizing universel

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
```

> **border-box** = padding et border inclus dans la largeur/hauteur
> Plus de calculs compliqués pour les dimensions !

---

## 🎨 Tâche 16 — Container centré

```css
.container {
  width: 960px;
  margin-left: auto;
  margin-right: auto;
}
```

> `margin: auto` = centrage horizontal automatique

---

## 🎨 Tâche 17 — Padding des sections

```css
:root {
  --section-padding: 5rem 0;
  --section-header-padding: 0 0 3rem;
  --section-body-padding: 0 0 3rem;
  --section-footer-padding: 3rem 0 0;
  --section-footer-align: center;
  --footer-padding: 5rem 0 1rem;
}

.section {
  padding: var(--section-padding);
}

.section-header {
  padding: var(--section-header-padding);
}

.section-body {
  padding: var(--section-body-padding);
}

.section-footer {
  padding: var(--section-footer-padding);
  text-align: var(--section-footer-align);
}

.footer {
  padding: var(--footer-padding);
}
```

---

## 🎨 Tâche 18 — Navbar personnalisée

```css
:root {
  --nav-item-font-family: var(--font-family-title);
  --nav-item-font-weight: var(--font-weight-bold);
  --nav-item-font-size: var(--font-size-medium);
  --nav-item-letter-spacing: 0.04rem;
  --nav-item-display: inline-block;
  --nav-item-margin: 0 0 3rem 0;
  --nav-item-link-hover: var(--color-primary);
}

.navbar-menu {
  float: right;
}

.nav {
  margin: 0;
  padding: 0;
  list-style: none;
  text-align: center;
}

.nav .nav-item {
  font-family: var(--nav-item-font-family);
  font-weight: var(--nav-item-font-weight);
  font-size: var(--nav-item-font-size);
  letter-spacing: var(--nav-item-letter-spacing);
  display: var(--nav-item-display);
  margin: var(--nav-item-margin);
}

.nav .nav-link {
  display: block;
  padding: 0.5rem 1rem;
}

.nav .nav-link:hover {
  color: var(--nav-item-link-hover);
}
```

---

## 🎨 Tâche 19 — Grille CSS avec floats

```css
:root {
  --section-tagline-margin: 0;
}

.section-tagline {
  margin: var(--section-tagline-margin);
}

/* Liste sans styles */
ul.row {
  margin: 0;
  padding: 0;
  list-style: none;
}

/* Colonnes */
.col-1-3 {
  width: 33.33%;
  float: left;
  padding: 0.5rem;
}

.col-1-2 {
  width: 50%;
  float: left;
  padding: 0.5rem;
}

/* Footer */
.footer ul {
  text-align: right;
}

.footer-copyright {
  margin: 0;
  font-size: var(--font-size-small);
  color: var(--text-color);
}
```

---

## 🎨 Tâche 20 — Clearfix

```css
/* Après chaque .row, nettoie les floats */
.row::after {
  content: "";
  display: table;
  clear: both;
}
```

> **Pourquoi ?** Sans clearfix, les éléments parents s'effondrent
> quand leurs enfants sont en `float`

---

## 🎨 Tâche 21 — Sélecteur col- simplifié

```css
/* Sélectionne toutes les classes qui commencent par "col-" */
[class^="col-"] {
  float: left;
  padding: 0.5rem;
}

/* Seulement la largeur pour chaque colonne */
.col-1-3 {
  width: 33.33%;
}

.col-1-2 {
  width: 50%;
}
```

> `[class^="col-"]` = sélecteur d'attribut qui commence par "col-"

---

## 🎨 Tâche 22 — Thème sombre (Dark theme)

```css
[data-section-theme="dark"] {
  --text-color: var(--color-white);
  --section-title-color: var(--color-white);
  background-color: var(--color-black);
}
```

> **Astuce puissante** : En redéfinissant les variables CSS dans ce
> sélecteur, TOUS les éléments enfants héritent automatiquement
> des nouvelles couleurs !

---

## 🎨 Tâche 23 — Footer et liens sociaux

```css
.footer-address {
  color: var(--text-color);
}

.social-link {
  display: block;
}

.social-link svg {
  fill: var(--text-color);
}
```

---

## 🎨 Tâche 24 — Cartes services

```css
.card-services .card-title {
  margin: 0;
}

.card-services a {
  display: block;
  padding: 2rem;
  background-color: var(--color-light-grey);
}

.card-services a:hover {
  color: var(--color-white);
  background-color: var(--color-primary);
  text-decoration: none;
}
```

---

## 🎨 Tâche 25 — Boutons

```css
:root {
  --button-display: inline-block;
  --button-padding: 1.5rem 3rem;
  --button-border: 0.2rem solid var(--color-primary);
  --button-color: var(--color-black);
  --button-text-decoration: none;
  --button-font-size: var(--font-size-large);
  --button-hover-color: var(--color-white);
  --button-hover-text-decoration: none;
  --button-hover-background: var(--color-primary);
}

.button {
  display: var(--button-display);
  padding: var(--button-padding);
  border: var(--button-border);
  font-size: var(--button-font-size);
  color: var(--button-color);
  text-decoration: var(--button-text-decoration);
}

.button:hover {
  color: var(--button-hover-color);
  text-decoration: var(--button-hover-text-decoration);
  background-color: var(--button-hover-background);
  transition-duration: var(--transition-duration);
  transition-property: color, background-color;
}

/* Dans dark theme */
[data-section-theme="dark"] {
  --button-color: var(--color-white);
}
```

---

## 🎨 Tâche 26 — Cartes témoignages

```css
.card-testimonial {
  text-align: center;
}

.card-testimonial .card-avatar {
  border-radius: 50%;      /* cercle parfait */
  width: 10rem;
  height: 10rem;
}

.card-testimonial .card-quote cite {
  display: block;
  padding-top: 1rem;
  color: var(--color-primary);
}
```

---

## 🎨 Tâche 27 — Section hero

```css
.section-hero {
  background-size: 90rem auto;
}

.section-hero .section-title {
  margin-bottom: 5rem;
}

.section-hero .section-inner {
  padding: 10rem 40rem 2rem 0;
}
```

---

## 🎨 Tâche 28 — Header et logo

```css
:root {
  --header-padding: 4rem 0 0;
  --header-logo-position: relative;
  --header-logo-link-display: inline-block;
  --header-logo-link-position: absolute;
  --header-logo-link-top: -1rem;
  --header-logo-link-left: 0;
}

.header {
  padding: var(--header-padding);
}

.header-logo {
  position: var(--header-logo-position);
}

.header-logo a {
  display: var(--header-logo-link-display);
  position: var(--header-logo-link-position);
  top: var(--header-logo-link-top);
  left: var(--header-logo-link-left);
}
```

---

## 🎨 Tâche 29 — Hover nav avec pseudo-élément

```css
/* Barre animée sous les liens nav */
.nav .nav-link::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  background-color: var(--color-white);
  width: 0;              /* largeur 0 par défaut */
  height: 0.2rem;
  transition: var(--transition-duration) var(--transition-cubic-bezier);
}

/* Au survol, la barre s'étend à 100% */
.nav .nav-item:hover .nav-link::before {
  background-color: var(--color-primary);
  width: 100%;
}
```

---

## 🎨 Tâche 30 — Section Works

```css
.card-work .card-outer {
  position: relative;
  overflow: hidden;     /* cache le débordement de l'image */
}

.card-work .card-image img {
  height: 30rem;
  width: 100%;
  object-fit: cover;    /* recadre l'image pour remplir */
  vertical-align: bottom;
}

.card-work .card-inner {
  position: absolute;
  top: -0.1rem;
  left: -0.1rem;
  right: -0.1rem;
  z-index: 1;
  transition: var(--transition-duration) var(--transition-cubic-bezier);
}

/* Overlay sombre au survol */
.card-work:hover .card-inner {
  background-color: rgba(0, 0, 0, 0.7);
}

.card-work .card-title {
  text-align: center;
  margin: 0;
  opacity: 0;           /* invisible par défaut */
  height: 100%;
  position: relative;
}

.card-work .card-title a {
  display: block;
  text-decoration: none;
  padding-top: 45%;
}

/* Lien cliquable sur toute la carte */
.card-work .card-title a::after {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
  content: "";
}

/* Titre visible au survol */
.card-work:hover .card-title {
  opacity: 1;
}
```

---

## 🎨 Tâche 31 — Décoration citations

```css
.card-testimonial .card-quote {
  position: relative;
}

/* Guillemet décoratif */
.card-testimonial .card-quote::before {
  content: "\201C";     /* code unicode du guillemet " */
  position: absolute;
  top: -4.5rem;
  left: -1rem;
  color: #efeded;
  font-size: 10rem;
  z-index: -1;          /* derrière le texte */
}
```

---

## 🎨 Tâche 32 — Transitions et animations

```css
:root {
  --transition-duration: .3s;
  --transition-cubic-bezier: cubic-bezier(0.17, 0.67, 0, 1.01);
}

/* Animation nav */
.nav .nav-link::before {
  transition: var(--transition-duration) var(--transition-cubic-bezier);
}

/* Animation bouton */
.button:hover {
  transition-duration: var(--transition-duration);
  transition-property: color, background-color;
}

/* Animation carte works */
.card-work .card-inner {
  transition: var(--transition-duration) var(--transition-cubic-bezier);
}

.card-work:hover .card-image {
  transform: scale(1.2);   /* zoom de l'image */
  transition: var(--transition-duration) var(--transition-cubic-bezier);
}

.card-work:hover .card-outer {
  transform: scale(0.95);  /* légère réduction de la carte */
}
```

---

## 📊 Récapitulatif des concepts utilisés

| Concept | Tâches | Exemple |
|---|---|---|
| Variables CSS | 3, 4, 5, 6, 7, 8 | `--color-primary: #d73953` |
| Pseudo-classes | 13, 24, 25, 29, 30 | `:hover`, `:visited`, `:active` |
| Pseudo-éléments | 20, 29, 30, 31 | `::before`, `::after` |
| Sélecteurs attribut | 21, 22 | `[class^="col-"]`, `[data-section-theme="dark"]` |
| Float + clearfix | 18, 19, 20 | `float: left` + `.row::after` |
| Position | 28, 29, 30, 31 | `relative`, `absolute` |
| Transitions | 32 | `transition: .3s cubic-bezier(...)` |
| Transformations | 32 | `transform: scale(1.2)` |
| Z-index | 30, 31 | `z-index: 1`, `z-index: -1` |
| Object-fit | 30 | `object-fit: cover` |
| Opacity | 30 | `opacity: 0` → `opacity: 1` |
| Box-sizing | 15 | `box-sizing: border-box` |
| Normalize | 14 | Reset navigateurs |
| Dark theme | 22 | Redéfinir variables dans sélecteur |

---

## 💡 Les patterns CSS importants à retenir

### Pattern 1 — Variable avec fallback
```css
color: var(--text-color, black);
/* Si --text-color n'existe pas, utilise black */
```

### Pattern 2 — Surcharge de variable pour thème
```css
:root { --color: black; }

.dark { --color: white; }
/* Tous les enfants de .dark utilisent white */
```

### Pattern 3 — Clearfix
```css
.row::after {
  content: "";
  display: table;
  clear: both;
}
```

### Pattern 4 — Overlay au survol
```css
.card { position: relative; }

.card .overlay {
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background: rgba(0,0,0,0);
  transition: .3s;
}

.card:hover .overlay {
  background: rgba(0,0,0,0.7);
}
```

### Pattern 5 — Lien cliquable sur toute une carte
```css
.card-title a::after {
  position: absolute;
  top: 0; right: 0; left: 0; bottom: 0;
  content: "";
}
```

### Pattern 6 — Animation de barre sous un lien
```css
.nav-link::before {
  content: "";
  position: absolute;
  bottom: 0; left: 0;
  width: 0;
  height: 2px;
  background: red;
  transition: width .3s ease;
}

.nav-item:hover .nav-link::before {
  width: 100%;
}
```

---

## ⚠️ Erreurs courantes à éviter

```css
/* ❌ MAUVAIS - oublier le commentaire en début de fichier */
html { scroll-behavior: smooth; }

/* ✅ BON */
/* Task 1 - Smooth scrolling */
html { scroll-behavior: smooth; }

/* ❌ MAUVAIS - mauvais ordre LVHA */
a:hover { }
a:link { }   /* trop tard ! */

/* ✅ BON */
a:link { }
a:visited { }
a:hover { }
a:active { }

/* ❌ MAUVAIS - oublier position: relative sur le parent */
.parent { }
.child { position: absolute; top: 0; }  /* se positionne par rapport à la fenêtre ! */

/* ✅ BON */
.parent { position: relative; }
.child { position: absolute; top: 0; }  /* se positionne par rapport au parent */
```

---

## 🚀 Commandes Git utilisées

```bash
# Créer un nouveau fichier CSS basé sur le précédent
cp styles/N-style.css styles/(N+1)-style.css


```

---

*Guide créé lors du projet CSS Advanced — Holberton School*

## Author
- **GitHub**: [sam99-web](https://github.com/sam99-web)
- **Repository**: holbertonschool-web_front_end
- **Directory**: html_advanced
