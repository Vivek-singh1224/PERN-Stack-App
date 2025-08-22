PERN Stack App (Postgres, Express, React, Node)

This project is built using the PERN stack and demonstrates a full-stack application setup with PostgreSQL as the database, Express/Node.js for the backend API, and React for the frontend.

🚀 Prerequisites

Before you begin, make sure you have installed:

Node.js & npm

PostgreSQL

Git

VS Code

📦 Installation

Clone the repository

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


Install server dependencies

cd server
npm install


Install client dependencies

cd ../client
npm install

🗄 Database Setup

Open PostgreSQL in your system and create a database:

CREATE DATABASE myapp;


Configure your database connection inside the server/.env file:

PGUSER=postgres
PGPASSWORD=yourpassword
PGHOST=localhost
PGDATABASE=myapp
PGPORT=5432
PORT=3001


Run migrations or manually create required tables (check server/db folder if schema is provided).

▶️ Running the Project in VS Code

Start the backend (Express + Node)

cd server
npm run dev


The backend runs at http://localhost:3001

Start the frontend (React)

cd client
npm start


The frontend runs at http://localhost:3000

📂 Project Structure
project-root/
│── client/         # React frontend
│── server/         # Node/Express backend
│── db/             # Database scripts/migrations
│── README.md

🛠 Tech Stack

Frontend: React

Backend: Express.js + Node.js

Database: PostgreSQL