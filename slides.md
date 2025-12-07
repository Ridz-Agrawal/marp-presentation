---
marp: true
theme: custom
paginate: true
paginate-position: bottom-right
title: Product Documentation Presentation
author: Riddhima Agrawal
---

<!--
This is the custom theme definition.
You can place it in the same file OR in a separate .css file.
-->

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
  color: #999;
}

/* Custom theme colors */
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

**Technical Writer**  
Riddhima Agrawal  
📧 *24f2004330@ds.study.iitm.ac.in*  

---

# 🎯 Why Marp?

- Write documentation in **Markdown**
- Convert easily to:
  - PDF
  - PPTX
  - HTML
- Perfect for **version control (Git/GitHub)**  
- Allows themes, diagrams, math, scripting, and automation  

---

# 🛠 Custom Theme in Use

This slide renders using the custom theme defined in the `<style>` block.

You can override styles using inline CSS or Marp directives:

```markdown
<!-- class: lead -->
