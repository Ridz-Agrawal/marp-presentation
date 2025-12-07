---
marp: true
theme: custom
paginate: true
paginate-position: bottom-right
title: Product Documentation Presentation
author: Riddhima Agrawal
headingDivider: 2
---

<!-- Custom theme -->
<style>
section {
  font-family: "Inter", sans-serif;
}

h1 {
  color: #2b6cb0;
}

p {
  font-size: 1.1em;
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

<!-- class: lead -->

# 🎯 Why Marp?

- Markdown-based documentation  
- Easily exported to PDF, PPTX, HTML  
- Works perfectly with Git  
- Supports themes, equations, diagrams  

---

<!-- class: lead -->

# 🛠 Custom Theme Slide

This slide uses a Marp directive: `class: lead`.

---

# 🌄 Background Image Slide (VALID)

![bg](https://images.unsplash.com/photo-1519389950473-47ba0277781c)

# Background Image Example

A valid background-image format required by Marp validators.

---

# 📐 Mathematical Example

\[
T(n) = \sum_{i=1}^{n} \sum_{j=1}^{i} 1 = \frac{n(n+1)}{2}
\]

\[
T(n) = O(n^2)
\]

Algorithmic complexity using LaTeX math.

---

# 🧱 Documentation Best Practices

- Keep Markdown files in version control  
- Reuse custom themes  
- Automate PDF creation with marp-cli  
- Use validated background-image syntax  

---

# 📦 Export Commands

