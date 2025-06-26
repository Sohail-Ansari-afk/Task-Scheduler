# ✨ Task-Scheduler

## 🧩 Projects Overview

1. 🔗 **URL Shortener (Flask)**
2. ⏰ **Task Scheduler with Notifications (Tkinter GUI)**

---

### 1️⃣ 🔗 URL Shortener

A minimal Flask-based application to shorten URLs and store them in a SQLite database.

---

### 📂 File Structure

```
URLShortener.py
urls.db (created automatically)
requirements.txt
```

---

### ⚙️ Installation & Running

#### 🧪 Step 1: Install Flask

```bash
pip install flask
```

Or use the requirements:

```bash
pip install -r requirements.txt
```

#### ▶️ Step 2: Run the App

```bash
python URLShortener.py
```

#### 🌐 Step 3: Open in Browser

Visit: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

### 🧪 Features

* Input a long URL → get a shortened link
* Visit short link → get redirected
* Uses `base62` encoding
* Saves all links in `urls.db`

---

### 2️⃣ ⏰ Task Scheduler with GUI & Notifications

A desktop Python GUI app to schedule tasks and get notifications at the right time.

---

### 📂 File Structure

```
TaskScheduler.py
tasks.db
requirements.txt
```

---

### ⚙️ Installation & Running

#### 🧪 Step 1: Install Required Packages

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install plyer schedule
```

#### ▶️ Step 2: Run the App

```bash
python TaskScheduler.py
```

---

### 🧪 Features

* 🖥️ GUI to add tasks (title, description, due time, repeat)
* ⏰ Notifies you at the exact time
* 🔁 Repeats task based on user setting (once, daily, weekly)
* 📦 Uses SQLite (`tasks.db`) to store and manage data

---

### ✅ Notes

* Use correct format: `YYYY-MM-DD HH:MM`
* Keep the app running in the background to receive timely notifications
* Cross-platform: works on Windows, Linux, and macOS

---

### 📜 License

MIT License

---
