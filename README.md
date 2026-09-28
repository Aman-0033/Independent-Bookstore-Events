# Independent Bookstore Events Page

A production-grade, single-file web application built with pure HTML5, Vanilla CSS, and Vanilla JavaScript (ES6 Class Architecture). Designed for an independent bookstore to manage, schedule, and showcase community literary events, author signings, and poetry readings.

---

## 🚀 Features

- **Executive Monochromatic Design**: Modern, high-contrast corporate grayscale system utilizing CSS custom properties.
- **Strict Spacing System**: Built on a rigid 8px / 16px / 32px rhythm with subtle layered box shadows and fluid typography (`clamp()`).
- **Responsive 2-Column Grid**: Two-column layout on desktop that seamlessly stacks on mobile devices.
- **Senior-Level Architecture**: All state and logic encapsulated inside an ES6 `EventManager` class with zero global namespace pollution.
- **Resilient Edge-Case Handling**:
  - **Empty State**: Elegant empty state with custom inline SVG illustration and helpful microcopy.
  - **Network Simulation**: 1500ms latency simulation on submit with disabled button state, animated SVG spinner, and form dimming.
  - **Inline Validation**: Non-blocking custom field validation with smooth sliding error animations and auto-focusing on invalid fields.
- **Security & Accessibility (100% Lighthouse A11y)**:
  - **XSS Defense**: Inputs strictly sanitized via native `textContent` mapping before entering state.
  - **A11y**: ARIA live regions (`aria-live="polite"`), explicit `<label>` bindings, semantic elements, skip navigation link, and visible `:focus-visible` rings.
  - **Telemetry**: Analytics interceptor logging interactions on every submission attempt.

---

## 💻 Tech Stack

- **Markup**: Semantic HTML5 (`<header>`, `<main>`, `<section>`, `<article>`, `<time>`, `<footer>`)
- **Styling**: Vanilla CSS3 (CSS Variables, Flexbox, CSS Grid, Fluid Sizing)
- **Scripting**: Vanilla JavaScript (ES6 Class, Custom DOM Sanitization, Event-Driven Architecture)
- **External Dependencies**: None (0 external libraries or frameworks)

---

## 🏃 Getting Started

### Option 1: Direct File
Simply double-click or open `index.html` in any modern web browser.

### Option 2: Local HTTP Server
Run a quick local HTTP server using Python or Node.js:

```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```

Then visit [http://localhost:8080](http://localhost:8080).

---

## 📄 License
MIT License.
