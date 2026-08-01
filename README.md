# ☕ Bean & Brew – Responsive Coffee Shop Landing Page

A beautifully crafted, modern, and fully responsive landing page built for a premium local coffee shop. This project showcases clean web interfaces using structural semantic HTML guidelines alongside the modern utility features of **Tailwind CSS v4.0**.

---

## ✨ Features

- **Tailwind CSS v4.0 Engine:** Fully implemented using the brand new CSS-first configuration and `@theme` variable injection.
- **Strict Semantic HTML Layout:** Built natively using zero layout wrappers or extra structural helper divs within layout segments, maximizing SEO and accessibility.
- **Mobile-First Responsive Design:** Seamless layout transformation across phone, tablet, and widescreen desktop monitors using pure Tailwind breakpoint utilities.
- **Premium Design Elements:** Includes a custom hero blend overlay mask, stylized drop-shadow card modules, custom interactive fields, and smooth transition animations.
- **Sophisticated Typography Duet:** Utilizes structural Google Fonts CDN configurations (`Syne` for modern bold headings and `Inter` for sleek body readability).

---

## 🎨 Design System (Tailwind v4.0 `@theme`)

This project uses the modern Tailwind v4.0 CSS configuration architecture located inside your main source stylesheet (`src/input.css`):

```css
@import "tailwindcss";

@theme {
  --font-heading: "Syne", sans-serif;
  --font-body: "Inter", sans-serif;
}
```

---

## 📂 Project Architecture

```text
├── image/                  # All curated graphics for the cafe layout
│   ├── Cappuccino.png
│   ├── Chocolate.png
│   ├── Cold Brew.png
│   ├── Espresso.png
│   ├── hero-bg-1.png
│   ├── hero-bg.png
│   ├── Latte.png
│   ├── Macho.png
│   └── our-story.png
├── src/
│   ├── input.css          # Main entry source file containing Tailwind directives
│   └── output.css         # Compiled production file outputted by the Tailwind CLI
├── .gitignore
├── Assignment Overview.md
├── package-lock.json
├── package.json
└── tailwind-assignment.html # Main semantic HTML code page
```

---

## 🚀 Quick Start & Development Installation

To compile and run this layout assignment project locally, follow these steps:

### 1. Compile Tailwind CSS v4.0
Run the watch compiler terminal script inside your workspace directory to compile `src/input.css` out into `src/output.css`:
```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

### 2. Launch Development Server
Open your root file `tailwind-assignment.html` using **VS Code Live Server**. Ensure your layout points to your compiled stylesheet in your head tags:
```html
<link rel="stylesheet" href="./src/output.css">
```

---

## 🛠️ Built With

- **HTML5** – Semantic, wrapper-free layout containers (`<section>`, `<article>`, `<form>`)
- **Tailwind CSS v4.0** – Modern utility framework & styling compiler engine
- **Google Fonts** – Premium typographic hierarchy integration (`Syne` & `Inter`)

---

📐 Developed with ❤️ for clean code and perfect coffee.
