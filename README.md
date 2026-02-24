🚀 SQL + Python Practice (Codespaces)
Welcome! 👋
This environment lets you practice SQL (SQLite) and Python directly in GitHub Codespaces.
✅ No installs
✅ No setup headaches
✅ Just write code and run it
🧩 Step 1 — Create Your Own Copy (IMPORTANT)
👉 Click Fork (NOT “Use this template”)
Go to this repository
Click Fork (top right)
Open your fork
Click:
Code → Codespaces → Create codespace on main
Your environment will build automatically 🚀
⚙️ Step 2 — One-Time Setup
In the Codespace terminal, run:
bash run install
Then open a new terminal and run:
run update
That’s it. You’re ready.
📂 Folder Structure
Only work inside these folders:
sql/      → SQL files (.sql)
python/   → Python files (.py)
Example:
sql/schema.sql
sql/queries.sql
python/app.py
▶️ How to Run Your Code
We use a simple command:
run
🟦 Run a SQL File
run sql/schema.sql
run sql/queries.sql
This runs your SQL against a database named:
practice.db
You do NOT need to create it — SQLite creates it automatically.
🟨 Run a Python File
run python/app.py
🔄 Get Latest Updates
To get updates from the instructor repository:
run update
This automatically:
Connects to the main repository
Pulls updates
Keeps your work safe
🧹 Reset the Database (Start Fresh)
If something breaks:
rm practice.db
Then rerun your schema file.
🛠 Useful Terminal Commands
📌 See Files
ls
ls sql
ls python
📌 Create New Files
Create SQL file:
touch sql/myfile.sql
Create Python file:
touch python/myscript.py
📌 Open Files in Editor
code sql/myfile.sql
code python/myscript.py
📌 Check Database File
ls practice.db
📌 Delete Database
rm practice.db
❗ Common Issues
🔴 "run: command not found"
Run:
bash run install
Then open a new terminal.
🔴 "No such file or directory"
Check spelling:
ls
ls sql
🔴 "table already exists"
Reset database:
rm practice.db
Then rerun your schema.
🧠 How This Works (For Curious Students)
You fork this repo
        ↓
Your fork connects to instructor repo
        ↓
run update pulls new changes
        ↓
You write code only in:
   sql/
   python/
System files are hidden so you only focus on coding.
🎓 What You Now Have
Clean SQL + Python practice environment
Automatic update system
No installation required
Works in browser
Same structure used in professional development