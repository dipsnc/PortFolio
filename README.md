# 🌟 Modern Developer Portfolio

A sleek, responsive, and dynamic personal portfolio website built with modern web technologies, featuring a **Glassmorphism** design and a seamless **Dark Mode** toggle.

This portfolio is designed to showcase skills, projects, and achievements in an engaging and accessible format.

---

## ✨ Features

* **Glassmorphism UI:** Unique design achieved with transparent, blurred `glass-card` elements for a futuristic look.
* **Tailwind CSS:** Fully responsive and utility-first styling for rapid development and high maintainability.
* **Dark/Light Theme Toggle:** User-friendly theme switching with local storage persistence for a customized experience.
* **Gradient Text:** Eye-catching titles using a CSS gradient background clip.
* **Smooth Scroll Navigation:** One-page design with smooth scrolling for easy navigation.
* **Neon Hover Effects:** Subtle, modern glow on interactive elements in dark mode.
* **Comprehensive Sections:** Includes Hero, About, Skills (with progress bars), Projects, Achievements, and Contact.

---

## 🚀 Quick Start

Follow these steps to get a copy of the project up and running on your local machine.

### Prerequisites

You only need a modern web browser to view this project locally. Since the CSS is loaded via a CDN, no build tools are strictly required to start.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/dipsnc/PortFolio.git
    cd Portfolio
    ```
2.  **Open the file:**
    Simply open the `index.html` file in your favorite web browser.

    ```bash
    open index.html # on macOS
    # or start index.html on Windows
    ```

---

## ⚙️ Customization

To make this portfolio your own, you'll need to modify the content within the `index.html` file.

### 1. Personal Content

Replace the placeholder text with your actual information:

* **Navigation:** Update `<span class="gradient-text">Name.Dev</span>` with your name or brand.
* **Hero Section:** Replace the name in `Hi, I'm <span class="gradient-text">Name</span>` and the introductory subtitle.
* **About Section:** Update the descriptive paragraph.
* **Resume Link:** Update the `href` attribute for the "Download Resume" button.
* **Project Links:** Replace the `#` placeholders with actual links for the **Code** and **Demo** buttons.
* **Contact Section:** Update the `mailto:` link and social icon links.

### 2. Skills Section

The skill bars are powered by an inline `style` attribute.

To change a skill level, find the relevant `div` and modify the **`style="width: XX%"`** property:

```html
<div class="h-2 rounded-full bg-gray-200 dark:bg-white/10">
    <div
        class="h-2 rounded-full bg-gradient-to-r from-purple-400 to-blue-400"
        style="width: 95%"
    ></div>
</div>
```

---

## 👥 Made by

- Sanika Salunkhe [GitHub](https://github.com/TechMe103)
- Diya Mondal [GitHub](https://github.com/dipsnc)
