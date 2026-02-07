# 📝 Task & Notes Manager (FastAPI + MongoDB + CLI)

A simple yet powerful **Task & Notes Management system** built using **FastAPI**, **MongoDB**, and a **Rich-powered CLI**.  
This project demonstrates real-world backend API design along with a professional command-line interface.

---

## 🚀 Features

### ✅ Backend (FastAPI)
- Create tasks or notes
- View all items
- Update task status, priority, tags, or due date
- Delete a single item
- Delete all items
- MongoDB integration
- Clean REST API design

### 💻 CLI Frontend (Rich)
- Animated welcome screen
- Add new tasks/notes
- View tasks in table format
- Update task status & priority
- Delete single or all tasks
- Colorful & professional terminal UI

---

## 🛠 Tech Stack

- **Python 3.10+**
- **FastAPI**
- **MongoDB**
- **Pydantic**
- **Rich**
- **Requests**
- **python-dotenv**

---

## 📁 Project Structure

```

.
├── main.py          # FastAPI backend
├── cli.py           # CLI frontend using Rich
├── .env             # Environment variables
├── requirements.txt
└── README.md

````

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/task-notes-manager.git
cd task-notes-manager
````

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
uri=mongodb+srv://<username>:<password>@cluster.mongodb.net/
```

---

## ▶️ Run the Application

### Start Backend Server

```bash
uvicorn main:app --reload
```

API will be available at:

```
http://127.0.0.1:8000
```

### Start CLI Application

```bash
python cli.py
```

---

## 📌 API Endpoints

| Method | Endpoint       | Description      |
| ------ | -------------- | ---------------- |
| GET    | `/`            | Health check     |
| POST   | `/add`         | Add task/note    |
| GET    | `/all`         | Get all items    |
| PUT    | `/update/{id}` | Update item      |
| DELETE | `/delete/{id}` | Delete one item  |
| DELETE | `/delete-all`  | Delete all items |

---

## 🖥 CLI Preview

* Animated welcome screen
* Interactive menu
* Rich tables for task listing
* Color-coded UI for clarity

---

## 🎯 Learning Outcomes

* REST API development using FastAPI
* MongoDB CRUD operations
* Environment variable handling
* CLI design using Rich
* Backend + frontend integration

---

## 📜 License

This project is open-source and available for learning and educational purposes.

---

## 👨‍💻 Author

**Subrata Pal**
B.Tech – Electronics & Communication Engineering
Python | FastAPI | MongoDB | Linux

```