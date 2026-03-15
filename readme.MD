# KAM UI | Multi-Page Design Identity & Portfolio

A high-fidelity, **mobile-first** web showcase built to present brand identities and design projects with a minimalist **Swiss Design** aesthetic. This project functions as a digital brand book, emphasizing structured grids, technical typography, and pure CSS-based graphic elements.

---

## 🚀 Project Overview

The repository is structured as a sequential, narrative-driven experience across three distinct project case studies. Every visual component—from the custom grid logo to the hardware mockups—is built using pure CSS to ensure a lightweight and scalable performance without relying on heavy image assets.

### 🔗 Project Navigation
* **Case 01: KAMUI** (`index.html`) – The foundational brand book detailing color systems and typography.
* **Case 02: Personal Portfolio** (`portfolio.html`) – A bold navigation entry point using a signature graphic frame.
* **Case 03: PIAS BLANCHE** (`pias.html`) – A deep-dive project page showcasing credentials, awards, and technical process illustrations.

---

## 🛠️ Technical Implementation

### 1. Signature CSS Components
* **The Grid Logo (A87H):** A custom 2x2 grid. It uses a `::after` pseudo-element to create a precise vertical bisector, ensuring branding remains crisp and responsive.
* **The Blue Frame System:** A decorative `.blue-frame` container that acts as a stage for hero imagery. It includes a `.graphic` layer with CSS-drawn lines and circles for architectural depth.
* **Procedural Mockups:**
    * **iMac:** Built using `clip-path` for the stand and specific `border-width` properties for the hardware "chin."
    * **Business Cards:** Utilizes `aspect-ratio: 1.6 / 1` and absolute positioning for realistic watermarking and front/back previews.

### 2. Design System & Typography
* **Primary Palette:** Grounded in a high-contrast professional palette:
    * **Royal Blue:** `#313A87` (Coated Blue 072 C)
    * **Deep Black:** `#10181F` (Coated Black 6 C)
    * **Technical Gray:** `#A3A8B7` (Coated 7667 C)
* **Font Pairings:**
    * **Interface:** *Avenir Next* / *Helvetica Neue* (Clean and professional).
    * **Metadata:** *Source Code Pro* / *Courier New* (Monospace for technical precision).

### 3. Visual Filters
To maintain a unified brand mood, all images utilize a complex CSS filter stack:
```css
filter: grayscale(100%) sepia(100%) hue-rotate(190deg) saturate(400%) contrast(1.2);