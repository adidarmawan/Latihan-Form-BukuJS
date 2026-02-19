📚 Manajemen Buku + Login System

A simple Book Management application built with HTML, Bootstrap, and Vanilla JavaScript.
This project implements authentication, CRUD operations, pagination, and form validation.

🚀 Features

🔐 Simple Login System (client-side session using localStorage)

➕ Create Book

📖 Read Book List

✏️ Update Book

🗑️ Delete Book

📑 Pagination (6 books per page)

✅ Form Validation

🧠 OOP using ES6 Class

🌐 Fetch API integration

🛠️ Tech Stack

HTML5

Bootstrap 5

Vanilla JavaScript (ES6)

json-server (for REST API simulation)

localStorage (for session handling)

🔑 Demo Login Account

You can use the following credentials:

Username	Password
adi	123
admin	admin
🌐 Live Demo

Frontend (GitHub Pages):
👉 https://adidarmawan.github.io/Latihan-Form-BukuJS/

⚙️ How to Run Locally (Full CRUD)

This project uses json-server as a mock backend.

Install json-server:

npm install -g json-server


Run the server:

json-server --watch db.json --port 3000


Open index.html in your browser.

API endpoint:

http://localhost:3000/books

📌 Notes

CRUD operations require json-server to be running.

GitHub Pages only supports frontend display.

Session authentication is handled via localStorage.
