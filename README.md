# Sip Happens Café — Feedback Application

A responsive React web application built with TypeScript and Vite that allows users to leave feedback (Good, Neutral, Bad) for Sip Happens Café, view real-time statistics, and reset the collected data.

## 🚀 Live Demo

[View Live App on Vercel](https://02-react-cafe-qku8.vercel.app/)

---

## 🛠️ Tech Stack & Tools

- **React 18** — UI library
- **TypeScript** — Static typing
- **Vite** — Fast frontend build tool
- **CSS Modules** — Scoped component styling
- **Modern Normalize** — Consistent cross-browser base styles

---

## ✨ Features

- **Interactive Voting**: Collects user feedback via `Good`, `Neutral`, and `Bad` options.
- **Calculated Statistics**: Computes total feedback count and positive feedback percentage on the fly without redundant state storage.
- **Conditional Rendering**:
    - Displays a `Notification` message when no votes have been recorded.
    - Shows `VoteStats` as soon as the first vote is registered.
    - Shows the `Reset` button dynamically when total votes are greater than `0`.
- **State Reset**: Clears all collected statistics back to initial zero values.

---

## 📂 Project Structure

```text

src/
├── components/
│   ├── App/
│   │   ├── App.module.css
│   │   └── App.tsx
│   ├── CafeInfo/
│   │   ├── CafeInfo.module.css
│   │   └── CafeInfo.tsx
│   ├── Notification/
│   │   ├── Notification.module.css
│   │   └── Notification.tsx
│   ├── VoteOptions/
│   │   ├── VoteOptions.module.css
│   │   └── VoteOptions.tsx
│   └── VoteStats/
│       ├── VoteStats.module.css
│       └── VoteStats.tsx
├── types/
│   └── votes.ts
├── declarations.d.ts
├── global.css
└── main.tsx
.gitignore
.prettierrc
eslint.config.js
index.html
package-lock.json
package.json
README.md
tsconfig.app.json
tsconfig.json
tsconfig.node.json
vite.config.ts

```

---

## 💻 Getting Started Locally

1. **Clone the repository:**

```bash
git clone [https://github.com/yulikafsd/02-react-cafe.git](https://github.com/yulikafsd/02-react-cafe.git)

```

2. **Navigate to the project directory:**

```bash
cd 02-react-cafe

```

3. **Install dependencies:**

```bash
npm install

```

4. **Start the development server:**

```bash
npm run dev

```
