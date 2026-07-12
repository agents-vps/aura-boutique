# AURA — Haute Couture & Joaillerie

A premium, highly interactive e-commerce landing page designed for a luxury fashion and fine jewelry brand. 

This artifact showcases an editorial aesthetic with high-fidelity micro-interactions, custom styling, an interactive visual ensemble customizer, and a seamless shopping bag drawer.

## 🏛️ Design System & Visual Identity

The design system of **AURA** is centered on minimalism, space, and dramatic contrast to elevate the products to works of art.

*   **Typography**: **Cormorant Garamond** (an elegant, delicate serif with stunning italic details for headlines) paired with **Inter** (a clean, geometric sans-serif for reading comfort and navigational structure).
*   **Color Palette**:
    *   **Noir Absolu (`#0B0B0C`)**: Immersive dark backdrops that ground the collections.
    *   **Albâtre Cream (`#FAF8F5`)**: Crisp and warm editorial backgrounds for high readability.
    *   **Poussière d'Or (`#C5A880`) / Gold (`#D4AF37`)**: Delicate metallic accents used selectively for focus states and interactions.
*   **Imagery**: Curated high-fashion silhouettes and raw precious mineral photography (high-resolution assets sourced from Unsplash).
*   **Depth & Elevation**: Borderless structures, using clean solid color blocking and translucent frosted-glass blurs (`backdrop-filter`) on the sticky navigation and drawers.

---

## ✨ Features & Micro-Interactions

### 1. The Atelier Customizer (Interactive Visual Ensemble)
The core interactive highlight of this landing page is the **Atelier Virtuel** (Atelier of Synergies):
*   **Seamless Toggles**: Select from haute couture pieces (*La Robe Obscure*, *Le Blazer Albâtre*) and fine jewelry (*Le Ras-de-Cou Aurélia*, *Les Cascades d'Émeraudes*).
*   **Dynamic Visual Render**: The main image frame and detail preview cross-fade and adapt based on your selected synergy.
*   **Bespoke Styling Report**: A live-updated poetic critique of the chosen pairing written in the brand's tone, reflecting the dynamic aesthetic combination.
*   **Atelier Booking**: A single CTA to add the entire composite ensemble to your bag or book an exclusive fitting.

### 2. Interactive Product Grid ("Pièces Maîtresses")
*   Hover over any product to reveal fluid zoom-in transitions and sliding action panels.
*   Includes **Aperçu Atelier** (Quick View) and **Ajouter au Sac** (Add to Bag) features.

### 3. Atelier Quick View Modal
*   Clicking **Aperçu Atelier** triggers a beautifully scaled center-aligned modal.
*   Pulls full product information, long editorial description, craftsmanship details, and offers direct purchase capability.

### 4. Sliding Shopping Bag Drawer
*   A premium, right-hand sliding panel with a frosted blur backdrop overlay.
*   Tracks cart items, quantities, and calculates the total price in real-time.
*   Allows the user to adjust quantities or remove items smoothly with immediate feedback.

---

## 🛠️ Tech Stack & Requirements

*   **HTML5 & CSS3**: Responsive, semantic structure.
*   **Tailwind CSS v4 (via CDN)**: Utility-first, highly customized configuration with custom design tokens (`luxury-black`, `luxury-gold`, etc.).
*   **Vanilla JavaScript**: Zero dependencies, performance-oriented state management for the cart, modal, and customizer.
*   **Google Fonts**: Pre-fetched Cormorant Garamond and Inter families.

---

## 🚀 Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/agents-vps/aura-boutique.git
   cd aura-boutique
   ```
2. Simply open `index.html` in your favorite modern browser:
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   ```

---

## ✒️ Author

Created with care under the direction of **Alexandre D.** for **AURA Atelier**. All rights reserved © 2026.
