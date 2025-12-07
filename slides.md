---
marp: true
theme: custom
paginate: true
paginate-position: bottom-right
title: Product Documentation Presentation
author: Riddhima Agrawal
---

<!-- Custom theme definition -->
<style>
section {
  font-family: "Inter", sans-serif;
}

h1 {
  color: #2b6cb0;
}

p {
  font-size: 1.15em;
}

footer {
  color: #666;
}

:root {
  --bg-color: #ffffff;
  --text-color: #1a202c;
}

section {
  background-color: var(--bg-color);
  color: var(--text-color);
}
</style>

# 📘 Product Documentation  
### Using Marp for Maintainable Tech Docs

**Technical Writer:** Riddhima Agrawal  
📧 *24f2004330@ds.study.iitm.ac.in*

---

# 🎯 Why Marp?

- Fully Markdown-based documentation  
- Easily exported to PDF / PPTX / HTML  
- Excellent for Git & CI/CD  
- Supports themes, equations, diagrams, and automation  

---

# 🛠 Custom Theme in Use

This slide is styled using the **custom theme** defined earlier.

You can override styles using inline CSS or classes.

---

<!-- class: lead -->

# ✨ Lead Slide (Custom Style)

This slide uses the `.lead` class to appear more dominant.

---

<!--
backgroundImage: "https://images.unsplash.com/photo-1519389950473-47ba0277781c"
backgroundSize: cover
-->

# 🌄 Background Image Slide

This slide contains a valid full-background image.

---

# 📐 Mathematical Example

Marp supports LaTeX-style math.

### Algorithmic Complexity

\[
T(n) = \sum_{i=1}^{n} \sum_{j=1}^{i} 1 = \frac{n(n+1)}{2}
\]

Which simplifies to:

\[
T(n) = O(n^2)
\]

---

# 🧱 Maintainability Best Practices

- Keep Markdown files in Git version control  
- Reuse themes across multiple decks  
- Automate PDF builds using Marp CLI in CI/CD  

---

# 📦 Export Commands

