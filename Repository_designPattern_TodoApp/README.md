# Todo List App - Laravel Repository Pattern

This is a **Todo List application** built with **Laravel** to demonstrate the **Repository Design Pattern** and clean architecture principles.

---

## 🚀 Features
- Create, view, and list todos
- Clean architecture using Repository Pattern
- Dependency Injection
- Separation of concerns
- Simple and clean **Bootstrap 5 UI**

---

## 🧱 Architecture
app/
├── Http/Controllers
│ └── TodoController.php
├── Repositories
│ ├── TodoRepository.php
├── Interfaces
│ └── TodoInterface.php
└── Models
└── Todo.php
resources/
└── views/
├── todos/
│ ├── layout.blade.php
│ ├── index.blade.php



---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/samijanghori/DesignPattern_inlaravel_presentation.git
Install dependencies:

2. composer install


Copy .env.example:

cp .env.example .env


Generate application key:

php artisan key:generate


Configure database in .env file

Run migrations:

php artisan migrate


Start the application:

php artisan serve**



