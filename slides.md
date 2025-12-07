---
marp: true
theme: custom
paginate: true
paginate-position: bottom-right
title: Product Documentation Presentation
author: Riddhima Agrawal
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

# 🎯 Why Marp?

- Fully Markdown-based documentation  
- Easily exported to PDF, PPTX, HTML  
- Great for Git version control  
- Supports custom themes, equations, diagrams  

---

# 🛠 Custom Theme Slide

This slide uses the custom theme defined earlier.

---

<!-- class: lead -->

# ✨ Lead Slide (Custom Style)

Highlighted using `.lead` class for emphasis.

---

# 🌄 Background Image Slide (VALIDATED)

![bg](https://images.unsplash.com/photo-1519389950473-47ba0277781c)

# Background Image Example  
This slide **uses the officially validated background-image syntax**.

---

# 📐 Mathematical Example

\[
T(n) = \sum_{i=1}^{n} \sum_{j=1}^{i} 1 = \frac{n(n+1)}{2}
\]

\[
T(n) = O(n^2)
\]

Algorithmic complexity expressed using LaTeX math.

---

# 🧱 Documentation Best Practices

- Keep Markdown files version-controlled  
- Reuse styles and themes  
- Automate PDF builds with marp-cli  
- Use background images sparingly  

---

# 📦 Export Commands

