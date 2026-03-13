# 📒 Todo Notebook & Weekly Planner

A beautifully designed **interactive notebook-style** productivity app built with React JS. Feels like a real spiral-bound notebook sitting on a wooden desk.

🔗 **Live Demo:** [todo-notebook-iota.vercel.app](https://todo-notebook-iota.vercel.app/)

---

## ✨ Features

- 📕 **Animated Book Cover** — App opens with a dark blue notebook cover. Click "Open Notebook" to reveal pages with a 3D flip animation.
- 🌀 **Real Spiral Binding** — Metallic gold/bronze SVG coil rings between the two pages
- 📝 **Todo List (Left Page)** — Add, edit (double-click), complete, and erase tasks. Max 18 tasks per page.
- 📅 **Weekly Planner (Right Page)** — Monday to Sunday editable grid with localStorage support
- 📄 **Multi-Page Support** — Pages fill up to 18 tasks, then flip to a new page with 3D animation
- ⬅️➡️ **Page Navigation** — Prev Page / Next Page / Close Book buttons
- 🖊️ **Desk Scene** — SVG pencil case, pens, STABILO markers, eraser, and water bottle
- 💾 **Local Storage** — All tasks and planner data are saved automatically
- 🎨 **Wooden Desk Background** — Realistic desk texture via CSS gradients

---

## 🛠️ Built With

- **React JS** — Component-based UI
- **CSS3** — Custom animations, 3D transforms, ruled lines, spiral binding
- **SVG** — Hand-crafted stationery decorations and spiral rings
- **Local Storage** — Persistent data without a backend
- **Vercel** — Deployment

---

## 📁 Project Structure

```
src/
├── App.js                  # Main entry — imports & state only
├── App.css
├── index.js
├── index.css               # Wooden desk background & fonts
│
├── components/
│   ├── BookCover.js        # Animated notebook cover
│   ├── DeskScene.js        # Stationery decorations (SVG)
│   ├── NotebookLayout.js   # Notebook wrapper + spiral + page flip
│   ├── TodoPage.js         # Left page — todo list
│   └── PlannerPage.js      # Right page — weekly planner
│
└── styles/
    ├── BookCover.css
    ├── NotebookLayout.css
    ├── TodoPage.css
    └── PlannerPage.css
```

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/beingtaha/todo-notebook.git

# Install dependencies
cd todo-notebook
npm install

# Run locally
npm start
```

---

## 👨‍💻 Developer

**Taha Ahmed**

- 🌐 Portfolio: [taha-portfolio-gold.vercel.app](https://taha-portfolio-gold.vercel.app)
- 💼 LinkedIn: [linkedin.com/in/tahaa-ahmed](https://www.linkedin.com/in/tahaa-ahmed/)
- 🐙 GitHub: [github.com/beingtaha](https://github.com/beingtaha)
