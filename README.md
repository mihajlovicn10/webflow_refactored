# Webflow AI-Refactor Showcase

A no-code Webflow project refactored with AI into clean, semantic HTML/CSS/JS and deployed via GitHub and Netlify.  
This project demonstrates how visual prototyping and full-code control can co-exist in a production-grade frontend workflow.

---

## 🚀 Project Overview

This project began as a Webflow visual draft. After exporting the code, the structure, styles, and logic were refactored using [Cursor IDE](https://www.cursor.so/) with GPT-4 integration.  
The final result is a fast, maintainable, and semantic codebase — deployed live using Netlify, and version-controlled via Git.

---

## 🧠 Technologies Used

- **Webflow** – Visual prototyping & design system  
- **Cursor IDE + GPT** – Semantic refactor & copy improvement  
- **Python (local server)** – Static file preview during development  
- **GitHub** – Version control & collaboration  
- **Netlify** – Deployment & hosting

---

## 🗂 Project Structure

/root
├── index.html
├── style.css
├── webflow.css
├── webflow-basic-[hash].css
├── normalize.css
├── scripts.js
├── images/
└── serve.py


- `webflow.css`: untouched Webflow core styles  
- `webflow-basic.css`: refactored user-defined styles  
- `scripts.js`: cleaned and modularized  
- `serve.py`: optional local server for preview

---

## ✅ Refactor Goals

- Replace `div`-heavy layout with semantic HTML5 structure (`section`, `main`, `article`, etc.)
- Improve class naming, accessibility, and responsiveness
- Rewrite copy (CTA, headers, microcopy) with conversion in mind
- Maintain visual integrity while removing Webflow dependency

---

## 💡 Why It Matters

This is more than a no-code experiment — it’s a demonstration of architectural awareness.  
Combining Webflow speed with dev-level control shows that clean code, versioning, and automation can live under the same roof as no-code tooling.

---

## 🧪 Local Preview

```bash
python3 serve.py
# Visit http://localhost:8080

