# Local Storage Task Tracker 📋

## 📌 Project Overview

The **Local Storage Task Tracker** is a simple task management web application developed using **HTML, CSS, and JavaScript**.

The application allows users to add, edit, complete, and delete tasks. All tasks are stored in the browser's **Local Storage**, so the tasks remain available even after refreshing or reopening the webpage.

## 🚀 Features

* Add new tasks
* Edit existing tasks
* Mark tasks as completed
* Delete tasks
* Save tasks using Local Storage
* Automatically load saved tasks
* Simple and responsive user interface
* Empty task validation
* Completed tasks displayed with a line-through style

## 🛠️ Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling and layout
* **JavaScript** – Task management and DOM manipulation
* **Local Storage API** – Persistent storage of tasks

## 💾 Local Storage

The project uses the browser's Local Storage to save task information.

Tasks are converted into JSON format before being stored:

```javascript
localStorage.setItem("tasks", JSON.stringify(tasks));
```

When the application starts, saved tasks are retrieved:

```javascript
JSON.parse(localStorage.getItem("tasks")) || [];
```

## 📂 Project Structure

```text
Task-5-Local-Storage-Task-Tracker/
│
├── index.html
└── README.md
```

## ▶️ How to Run

1. Download or clone the repository.
2. Open the project folder in VS Code.
3. Open `index.html` in a web browser.
4. Enter a task in the input box.
5. Click **Add**.
6. Use the available buttons to complete, edit, or delete tasks.

You can also use the **Live Server** extension in VS Code.

## 🔍 How It Works

### Add Task

The user enters a task and clicks the **Add** button. The task is added to the task array and saved in Local Storage.

### Complete Task

Clicking the **✔** button changes the task's completion status. Completed tasks are displayed with a line-through effect.

### Edit Task

Clicking the **Edit** button allows the user to modify an existing task.

### Delete Task

Clicking the **Delete** button removes the selected task from the task list and Local Storage.

### Persistent Data

Tasks remain saved after refreshing the browser because the application uses Local Storage.

## 🎯 Internship Task

**Task:** Task 5 – Local Storage Task Tracker

**Domain:** Web Development

**Technologies:** HTML, CSS, JavaScript, Local Storage API

## 👩‍💻 Author

**Balasala Nandini**

## 📄 License

This project is created for educational and internship purposes.
