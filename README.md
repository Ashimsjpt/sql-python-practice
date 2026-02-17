# 🚀 SQL + Python Practice (Codespaces)

Welcome! 👋  
This environment lets you practice **SQL (SQLite)** and **Python** directly in GitHub Codespaces.

No installs.  
No setup headaches.  
Just write code and run it.

---

# 🧩 Step 1 — Create Your Own Copy

1. Click **Use this template**
2. Create your own repository
3. Open it in **Codespaces**
   - Click **Code → Codespaces → Create codespace on main**

Your environment is ready.

---

# 📂 Folder Structure

Use these folders:

- `sql/` → for SQL files (`.sql`)
- `python/` → for Python files (`.py`)

Example:

```
sql/schema.sql
sql/queries.sql
python/app.py
```

---

# ▶️ How to Run Your Code

We use a simple command called:

```
run
```

---

## 🟦 Run a SQL File

```bash
run sql/schema.sql
run sql/queries.sql
```

This runs your SQL against a database named:

```
practice.db
```

You DO NOT need to create the database.
SQLite creates it automatically.

---

## 🟨 Run a Python File

```bash
run python/app.py
```

---

# 🔄 Reset the Database (Start Fresh)

If something breaks or you want a clean start:

```bash
rm practice.db
```

Then rerun your SQL files.

---

# 🛠 All Useful Bash Commands

Here are all the terminal commands you might need:

---

## 📌 See Files

```bash
ls
ls sql
ls python
```

---

## 📌 Create New Files

Create a SQL file:

```bash
touch sql/myfile.sql
```

Create a Python file:

```bash
touch python/myscript.py
```

---

## 📌 Open Files in Editor

```bash
code sql/myfile.sql
code python/myscript.py
```

---

## 📌 Check Database File

```bash
ls practice.db
```

---

## 📌 Delete Database

```bash
rm practice.db
```

---

# ❗ Common Issues

### "run: command not found"

Open a new terminal:

**Terminal → New Terminal**

Then try again.

---

### "No such file or directory"

Check spelling and folder:

```bash
ls
ls sql
```

---

### "table already exists"

Reset the database:

```bash
rm practice.db
```

Then rerun your schema file.

---
