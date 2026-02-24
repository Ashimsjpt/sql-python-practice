# 🚀 SQL + Python Practice (Codespaces)

Welcome! 👋  
This environment lets you practice SQL (SQLite) and Python directly in GitHub Codespaces.

✅ No installs  
✅ No setup headaches  
✅ Just write code and run it  

---

## 🧩 Step 1 — Create Your Own Copy (IMPORTANT)

👉 Click Fork (NOT "Use this template")

- Go to this repository  
- Click Fork (top right)  
- Open your fork  
- Click: Code → Codespaces → Create codespace on main  

Your environment will build automatically 🚀

---

## ⚙️ Step 2 — One-Time Setup

In the Codespace terminal, run:

```bash
bash run install
```

Then open a new terminal and run:

```bash
run update
```

That’s it. You’re ready.

---

## 🔄 IMPORTANT — Every Time You Start Codespaces

Whenever you open your Codespace again in the future, always run:

```bash
run update
```

This ensures:

- You receive the latest instructor updates  
- Your environment stays in sync  
- Your work remains safe  

Think of this as your **daily start command**.

---

## 📂 Folder Structure

Only work inside these folders:

- **sql/** → SQL files (.sql)  
- **python/** → Python files (.py)  

Example:

```text
sql/schema.sql
sql/queries.sql
python/app.py
```

---

## ▶️ How to Run Your Code

We use a simple command:

```bash
run
```

---

### 🟦 Run a SQL File

```bash
run sql/schema.sql
run sql/queries.sql
```

This runs your SQL against a database named:

```text
practice.db
```

You do NOT need to create it — SQLite creates it automatically.

---

### 🟨 Run a Python File

```bash
run python/app.py
```

---

## 🧹 Reset the Database (Start Fresh)

If something breaks:

```bash
rm practice.db
```

Then rerun your schema file.

---

## 🛠 Useful Terminal Commands

### 📌 See Files

```bash
ls
ls sql
ls python
```

---

### 📌 Create New Files

Create SQL file:

```bash
touch sql/myfile.sql
```

Create Python file:

```bash
touch python/myscript.py
```

---

### 📌 Open Files in Editor

```bash
code sql/myfile.sql
code python/myscript.py
```

---

### 📌 Check Database File

```bash
ls practice.db
```

---

### 📌 Delete Database

```bash
rm practice.db
```

---

## ❗ Common Issues

### 🔴 "run: command not found"

Run:

```bash
bash run install
```

Then open a new terminal.

---

### 🔴 "No such file or directory"

Check spelling:

```bash
ls
ls sql
```

---

### 🔴 "table already exists"

Reset database:

```bash
rm practice.db
```

Then rerun your schema.

---

## 🎓 What You Now Have

✅ Clean SQL + Python practice environment  
✅ Automatic update system  
✅ No installation required  
✅ Works in browser  
✅ Same structure used in professional development