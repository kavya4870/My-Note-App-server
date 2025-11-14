# My-Note-App-server
📘 My Note App

A simple full-stack notes application that allows users to add, edit, delete, search, and view notes with timestamps.
Built using:

React + Vite (Frontend)

Node.js + Express (Backend)

MongoDB Atlas (Database)

🚀 How to Run the App (Simple Steps)
1️⃣ Clone the project
git clone https://github.com/YOUR_USERNAME/my-note-app.git

🖥 Backend Setup

Go to the backend folder:

cd Backend


Install required packages:

npm install


Create a .env file inside the Backend folder and add:

MONGO_URI=your_mongodb_connection_string
PORT=5000


Start the backend server:

node server.js


The backend will run at:

http://localhost:5000

🌐 Frontend Setup

Go to the project root (frontend folder):

cd my-note-nexus-main


Install dependencies:

npm install


Start the frontend:

npm run dev


Frontend will run at:

http://localhost:5173

📦 API Endpoints
Method	Endpoint	Description
GET	/notes	Get all notes
POST	/notes	Add a new note
PUT	/notes/:id	Update a note
DELETE	/notes/:id	Delete a note
🗄 MongoDB Setup (Simple)

Create a MongoDB Atlas account

Create a free cluster

Add your current IP Address

Create a Database User

Get your connection string

Paste it inside your .env file as:

MONGO_URI=your_connection_string


That’s it!

✔ Features

Add Notes

Edit Notes

Delete Notes

Search notes

Timestamps (Created & Updated)

Pagination

Dark/Light theme
