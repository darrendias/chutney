# 🎓 Darren’s EdTech Tools Suite — Built for International Students

A modern, ultra-premium, and fully responsive suite of four unified tools designed to guide international students through their journey to and across the United Kingdom. 

Built with an elegant, cohesive visual identity, this project elevates raw functional utilities into an engaging, high-end digital experience that feels alive, premium, and seamless.

---

## 🎨 The Design Philosophy: Cream & Cocoa

Every interface in the suite is built from the ground up on a harmonious, dual-theme design system designed to wow visitors at first glance.

*   **🍦 Cream Theme (Light Mode):** A warm, luxurious palette of soft off-whites, warm tans, subtle sand borders, and deep charcoal text that feels organic and inviting.
*   **🍫 Cocoa Theme (Dark Mode):** A sleek, high-contrast, premium aesthetic built with dark chocolate backgrounds, translucent glassmorphic containers, and glowing ambient overlays.

### Key Interaction & Visual Features:
*   **🔄 Persistent State Synchronization:** Theme selections (Cream or Cocoa) are automatically stored in `localStorage` and synchronized across all open tabs in real-time, delivering a unified system feeling.
*   **🖱️ Cursor-Spotlight Glows:** A dynamic mouse-tracking visual system. Moving your cursor over cards and buttons casts an elegant radial spotlight glow (`--mouse-x` and `--mouse-y` dynamically updated via vanilla JS triggers).
*   **✨ Translucent Glassmorphism:** Layered glass card overlays using backdropped blurs, soft inner-glow highlights, and HSL-mapped borders that prevent color blowing on darker screens.
*   **📱 Native Fluid Responsiveness:** Painstakingly designed layouts that scale seamlessly from dual 4K monitors down to ultra-compact `320px` mobile viewports. Layouts collapse into vertical stacks with perfectly scaled tap-targets.

---

## 🚀 The Four Core Student Apps

### 1. 🌶️ Chutney — Find Your People in the UK
*   **File:** [`chutney.html`](file:///Users/thedarrendias/Downloads/chutney/chutney.html)
*   **The Insight:** Most international communities lump people together strictly by nationality. But sharing a passport doesn't mean sharing an identity. Chutney connects students based on **shared interests, cultural roots, and active intent**.
*   **Features:**
    *   A rapid 2-minute onboarding form collecting university, home state, hobbies, and social expectations.
    *   Categorized matching tags (Sports, Creative, Social, Career) mapping students directly to active group circles.
    *   Clean custom badges, beautiful grid alignments, and custom vector icons.

### 2. 🎓 UniMatch AI — Smart University Shortlister
*   **File:** [`shortlister.html`](file:///Users/thedarrendias/Downloads/chutney/shortlister.html)
*   **The Insight:** Searching for a university in a foreign country is overwhelming. UniMatch AI acts as a digital advisor to curate options based on real priorities.
*   **Features:**
    *   Interactive 5-question profile survey (Budget, Location, Career Focus, Lifestyle, Rank importance).
    *   Tailored top-3 custom university recommendations complete with dynamic match percentage indicators.
    *   AI-style personalized logic justifying why each university matches your precise lifestyle and career objectives.

### 3. 🗓️ VisaPath UK — Timeline & Checklist Builder
*   **File:** [`visa-timeline.html`](file:///Users/thedarrendias/Downloads/chutney/visa-timeline.html)
*   **The Insight:** Navigating student visa timelines can be stressful with strict, scattered country-specific deadlines.
*   **Features:**
    *   Dynamic dropdown filters mapping out checklist steps based on your country of origin and intake season (January, May, or September).
    *   An elegant, solid vertical timeline track embedded with metallic, dual color-coded status studs (Teal & Gold).
    *   Highlighted critical warnings, structured countdown trackers, and intuitive mobile stacking layouts.

### 4. 💸 CostCheck UK — Multi-City Budget Comparator
*   **File:** [`cost-compare.html`](file:///Users/thedarrendias/Downloads/chutney/cost-compare.html)
*   **The Insight:** Estimating student expenditures is notoriously difficult because London pricing differs wildly from other regions.
*   **Features:**
    *   A clean comparison matrix table aligning rent, groceries, transit, and social allowances.
    *   Horizontal-scrolling table guards (`overflow-x: auto`) keeping comparison metrics readable and side-by-side even on small smartphone screens.
    *   Translucent student advice panels highlighting money-saving tips and regional budget insights.

---

## 🛠️ Tech Stack & Architecture

This suite was built to prove that premium, ultra-modern web experiences do not require heavy frameworks or slow bundlers.

*   **Core Logic:** Pure, Vanilla JavaScript (ES6+).
*   **Styling & FX:** Advanced CSS3 Custom Properties (variables), Flexbox, CSS Grid layouts, backdrop filters, and custom cubic-bezier transitions.
*   **Zero Dependencies:** No React, no Tailwind, no external packages. Pages load instantly, cache easily, and require zero configuration to run.
*   **Inline Assets:** Equipped with an ultra-lightweight, uniform academic favicon (`🎓`) utilizing a browser-native SVG URL representation. No external icon assets required.
    ```html
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🎓</text></svg>">
    ```

---

*Built with passion by **Darren Dias** · MSc Digital Marketing, Royal Holloway, University of London.*
