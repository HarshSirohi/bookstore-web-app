🏪 Bookstore Web App

A full-stack web application for managing and browsing books online.
Built using React.js (Frontend) and Node.js + Express + MongoDB (Backend).

🚀 Project Structure
bookstore-web-app/
│
├── frontend/   # React.js frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/    # Node.js backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── server.js
│   └── package.json
│
└── README.md

🧠 Features

📚 Browse and search for books

🛒 Add books to cart

👤 User login and signup authentication

💾 MongoDB database integration

⚡ Full-stack CRUD functionality

🔐 JWT-based authentication

🎨 Responsive frontend UI

⚙️ Technologies Used
Area	Technologies
Frontend	React.js, Tailwind CSS / Bootstrap
Backend	Node.js, Express.js
Database	MongoDB, Mongoose
Version Control	Git & GitHub
Package Managers	npm / yarn
🧩 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/HarshSirohi/bookstore-web-app.git
cd bookstore-web-app

2️⃣ Setup Backend
cd backend
npm install


Create a .env file inside the backend/ folder and add the following:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Run the backend server:

npm start


Backend will run on:
👉 http://localhost:5000

3️⃣ Setup Frontend

Open a new terminal and run:

cd frontend
npm install
npm run dev


Frontend will run on:
👉 http://localhost:5173

🧪 Testing the App

Run both backend and frontend servers.

Open your browser and visit http://localhost:5173.

Register a user, browse books, and try adding to cart.

MongoDB database will automatically store and update records.