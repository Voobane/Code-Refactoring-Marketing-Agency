# ♿ Code Refactoring — Horiseon Marketing Agency

An accessibility-focused refactor of a marketing agency landing page. The original site was built with non-semantic `<div>` soup; this refactor replaces generic elements with semantic HTML5, adds descriptive `alt` attributes, fixes the heading hierarchy, and improves the page title — without changing the visual appearance.


---

## 📖 Overview

This project is a real-world example of what developers encounter when inheriting legacy code. The goal wasn't to redesign anything — it was to make the existing page more accessible for screen readers and assistive technologies, and to leave the codebase in better shape than it was found.

---

## ✨ Changes Made

- 🏷️ Replaced `<div>` wrappers with semantic elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>`
- 🖼️ Added descriptive `alt` attributes to every image and icon (or `alt=""` for decorative images)
- 📐 Fixed heading hierarchy — headings now descend in order (`h1` → `h2` → `h3`)
- 📝 Updated `<title>` to a descriptive, meaningful value
- 🔗 Fixed a broken anchor link in the navigation bar
- 🧹 Consolidated redundant CSS selectors and added comments throughout

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 (semantic elements) |
| Styling | CSS3 |
| Deployment | GitHub Pages |

---

## 🚀 Getting Started

No install required — open directly in a browser.

```bash
git clone https://github.com/Voobane/Code-Refactoring-Marketing-Agency.git
cd Code-Refactoring-Marketing-Agency
open index.html
```

---

## 📁 Project Structure

```
Code-Refactoring-Marketing-Agency/
├── index.html          # Refactored semantic HTML
├── assets/
│   ├── css/
│   │   └── style.css   # Cleaned up and consolidated styles
│   └── images/         # All site images (unchanged)
└── README.md
```

---

## 💡 What I Learned

- Why **semantic HTML** matters for accessibility and SEO — `<section>` and `<nav>` communicate meaning that `<div>` cannot
- How **screen readers** rely on `alt` text, heading hierarchy, and landmark elements to navigate a page
- How to **audit existing code** and prioritize changes by impact rather than scope
- The value of **CSS consolidation** — fewer, better-named selectors make styles easier to maintain
- The difference between **decorative** and **informative** images, and how to handle each with `alt`

---

## 📸 Screenshots

> _Add a before/after screenshot comparing the original div-heavy markup to the refactored semantic HTML._

---

## 👤 Author

**Matt (Voobane)**
- GitHub: [@Voobane](https://github.com/Voobane)
