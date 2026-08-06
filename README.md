# 🍋 Little Lemon Restaurant

> 🚀 **Live Demo:** [View Deployment](https://muneeb0346.github.io/Little-Lemon/)
> 

A high-end, fully responsive landing page for a family-owned Mediterranean restaurant, built to demonstrate advanced semantic markup and modern CSS architecture.

*This project was developed as the capstone for the Meta "HTML and CSS in Depth" course, serving as a practical application of baseline web technologies to create a production-grade, highly performant web experience.*

## 💡 The Backstory: Mastering the Fundamentals

While modern web development is often dominated by heavy JavaScript frameworks and utility-first CSS libraries, building a truly resilient and accessible web experience starts with the raw fundamentals. I took this as an engineering challenge to deliver a pixel-perfect, high-performance webpage relying exclusively on pure HTML and CSS.

This project focuses on strict semantic structuring and a scalable custom CSS architecture. The result is a lightweight, zero-dependency application that perfectly balances aesthetic design with absolute baseline performance.

## 🚀 The Execution & Features

* **Semantic Overhaul:** Constructed the document using strictly semantic HTML5 tags like `<header>`, `<main>`, `<article>`, and description lists (`<dl>`), ensuring proper document outline and enhanced screen-reader compatibility.


* **Scalable CSS Architecture:** Implemented a robust design system using CSS Custom Properties (`:root` variables) for consistent spacing, typography, and color management across the application.


* **Responsive Fluidity:** Engineered a fluid layout utilizing CSS Grid and Flexbox, paired with strategic media queries to ensure a seamless layout shift from large 1440px desktop displays down to 480px mobile screens.


* **Zero-Dependency Ecosystem:** Removed all reliance on external CSS frameworks or JavaScript libraries, keeping the payload incredibly light and the Time to Interactive (TTI) near instant.

## 🧠 Engineering & Technical Implementation

* **Advanced Layout Techniques:** Utilized a 3-column CSS Grid for the menu cards that gracefully degrades to a single column on smaller devices. Flexbox was leveraged for internal component alignment and navigation layout.


* **SEO & Open Graph Optimization:** Integrated comprehensive meta descriptions and Open Graph tags (`og:title`, `og:description`, `og:url`) to ensure rich link previews and maximum search engine visibility.


* **Performance & Asset Delivery:** Optimized the critical rendering path by using modern `.webp` image formats and locally hosting custom `@font-face` typography (Karla and Markazi Text) to prevent render-blocking external requests.


* **UI Micro-Interactions:** Added silky-smooth hover states, color transitions, and scale transforms with custom CSS transition timings to enhance user engagement without sacrificing main-thread performance.



## 🛠️ Tech Stack

* **Markup:** Semantic HTML5, Open Graph Meta Tags


* **Styling:** CSS3 (Custom Architecture, CSS Variables, Grid & Flexbox)


* **Performance Focus:** Zero-dependency architecture, WebP asset optimization, locally hosted fonts



## 📂 Directory Structure

```text
Little-Lemon/
├── favicon/                # Web manifest and multi-resolution favicons (SVG, PNG, ICO)
├── fonts/                  # Locally hosted custom typography (Karla, Markazi Text)
├── images/                 # Optimized .webp image assets for cards and banners
├── logos/                  # Brand assets and responsive logos
├── index.html              # Main entry point (Semantic HTML5 document)
└── styles.css              # Custom CSS architecture, resets, and global styles

```

## 💻 Local Installation

Because this project relies entirely on native browser rendering and a zero-dependency codebase, no package managers (like npm or yarn) are required to run it locally.

1. **Clone the repository:**

```bash
   git clone https://github.com/muneeb0346/Little-Lemon.git
   cd Little-Lemon

```

2. **Run the application:**
Simply open the `index.html` file in your preferred modern web browser.

*Alternatively, if you are using VS Code, you can launch it using the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for hot-reloading during development.*
