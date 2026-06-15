# Aayu Language 🚀

**Aayu** is a brand new, highly readable, intent-driven programming language designed to bridge the gap between human thought and executable code.

## 🧠 How it Works

Aayu follows a clean, modern compilation pipeline:
**Human Intent** → **Aayu Code** → **AST (Abstract Syntax Tree)** → **Execution**

The language features a custom lexer, parser, and interpreter, enabling features like structured records, variable declarations, loops, error handling, and tasks (functions) in a natural syntax.

---

## 📂 Projects

### 1. Authentication System (Pure Aayu)
This repository contains a functional **Authentication System** built entirely in **Pure Aayu** to demonstrate the language's capabilities.

**Features Implemented:**
- `User` entity records.
- Modularized architecture using Aayu's `use` keyword (Database, Auth, and API layers).
- Custom tasks for user registration, login, and logout.
- Simulated API layer execution.

#### Example: `user.aayu`
```aayu
record User.
    username
    password
end.
```

#### Example: `main.aayu`
```aayu
use api.

show "=== Auth System ===".

run start_server.

show "POST /register".
run register_user.

show "POST /login".
run login_user.

show "POST /logout".
run logout_user.
```

---

## 🚀 Running the Project

Ensure you have Python installed to run the interpreter.

```bash
python run.py project_9_auth_system/main.aayu
```

**Expected Output:**
```text
=== Auth System ===
API Started
POST /register
User Registered
POST /login
Login Success
POST /logout
Logout Success
```

---

## 🛠️ Future Roadmap (Phase 2)

Aayu is rapidly evolving! The next steps for the language include:
1. **Building more Real-World Projects:**
   - Project-9 Authentication System v2 (Adding File I/O Database)
   - Student Management System
   - Task Manager
   - Mini Web Backend
2. **Aayu Specification v1.0:** Freezing the syntax and features.
3. **VS Code Extension:** Adding official syntax highlighting and IntelliSense for `.aayu` files.
4. **GitHub Linguist PR:** Registering Aayu as an official GitHub language!