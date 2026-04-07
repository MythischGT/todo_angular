# ✅ Angular ToDo App

> Part of the **Angular Learning Series** — a hands-on journey through Angular fundamentals, one project at a time.

---

## 📖 About

This is a simple, fully functional **ToDo application** built with Angular. It was created as part of my personal Angular Learning Series to practice and demonstrate core Angular concepts in a practical setting.

---

## 🎯 Learning Objectives

This project covers the following Angular fundamentals:

- **Components** — Creating and structuring reusable UI components
- **Data Binding** — One-way and two-way binding with `[(ngModel)]`
- **Directives** — Using built-in directives like `*ngFor` and `*ngIf`
- **Event Handling** — Responding to user interactions with `(click)` and `(keyup)`
- **Services & Dependency Injection** — Managing shared state through a `TodoService`
- **TypeScript Interfaces** — Modeling data with typed interfaces
- **Component Communication** — Passing data with `@Input()` and `@Output()`

---

## 🚀 Features

- ➕ Add new tasks
- ✔️ Mark tasks as complete / incomplete
- 🗑️ Delete tasks
- 📋 Filter tasks by status (All / Active / Completed)
- 💾 Persistent storage via `localStorage`

---

## 🛠️ Tech Stack

| Technology | Version |
|---|---|
| Angular | 17+ |
| TypeScript | 5+ |
| Angular CLI | 17+ |
| Node.js | 18+ |

---

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [Angular CLI](https://angular.io/cli)

```bash
npm install -g @angular/cli
```

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/MythischGT/todo_angular.git
cd todo_angular
```

2. **Install dependencies**

```bash
npm install
```

3. **Run the development server**

```bash
ng serve
```

4. Open your browser and navigate to `http://localhost:4200`

---

## 📁 Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── todo-list/        # Renders the list of todo items
│   │   ├── todo-item/        # Individual todo item component
│   │   └── todo-form/        # Input form for adding new tasks
│   ├── models/
│   │   └── todo.model.ts     # Todo interface definition
│   ├── services/
│   │   └── todo.service.ts   # Business logic & state management
│   ├── app.component.ts
│   └── app.module.ts
└── ...
```

---

## 📚 Angular Learning Series

This project is part of a series of projects I'm building to learn Angular progressively:

| # | Project | Topics Covered |
|---|---|---|
| 1 | **ToDo App** ← *you are here* | Components, Directives, Services, Data Binding |
| 2 | Coming soon... | Routing, Guards, Lazy Loading |
| 3 | Coming soon... | HTTP Client, RxJS, Observables |

---

## 🤝 Contributing

This is a personal learning project, but feedback and suggestions are always welcome! Feel free to open an issue if you spot something or have ideas for improvement.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> *Learning Angular, one commit at a time.* 🚀