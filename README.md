Store Rating System — Full Stack Project

A complete full-stack web application built using FastAPI, Streamlit, and MySQL.
This project allows users to sign up, log in, browse stores, and submit ratings.
It demonstrates end-to-end full-stack development including API creation, authentication, UI handling, state management, and database integration.

📌 Features

🔐 User Authentication — Signup & Login

⭐ Store Rating System

🏬 View All Stores with details

📊 Average rating updated automatically

⚙️ Backend REST APIs using FastAPI

🎨 Frontend UI using Streamlit

🗄️ MySQL database using SQLAlchemy ORM

🔗 Smooth integration between frontend & backend

🗂️ Project Structure
project/
│── backend/
│   ├── main.py
│   ├── models.py
│   ├── schemas.py
│   ├── routers/
│   └── database.py
│
│── frontend/
│   └── app.py
│
└── README.md

🚀 Getting Started

Follow the steps below to run MySQL, Backend, and Frontend on your system.

🗄️ 1. Setup MySQL Database

Start MySQL (Workbench / XAMPP / WAMP / Local Server).

Create the database:

CREATE DATABASE rating_app;


Configure database connection in backend/database.py:

SQLALCHEMY_DATABASE_URL = "mysql+pymysql://<username>:<password>@localhost/rating_app"


Replace <username> and <password> with your MySQL credentials.

⚙️ 2. Run the Backend (FastAPI)
Step 1 — Open a terminal in the backend folder:
cd backend

Step 2 — Install dependencies:
pip install -r requirements.txt

Step 3 — Start the backend server:
uvicorn backend.main:app --reload

Backend available at:
http://127.0.0.1:8000

API Documentation:
http://127.0.0.1:8000/docs

🎨 3. Run the Frontend (Streamlit)
Step 1 — Open a new terminal in the frontend folder:
cd frontend

Step 2 — Install frontend dependencies:
pip install -r requirements.txt

Step 3 — Start Streamlit:
streamlit run app.py

Frontend opens at:
http://localhost:8501

🔄 Workflow Summary
Component	Command	URL
Backend	uvicorn backend.main:app --reload	http://127.0.0.1:8000

Frontend	streamlit run app.py	http://localhost:8501

MySQL DB	Create DB + run server	—

Steps to run the project:

Start MySQL

Run backend

Run frontend

Sign up → log in → browse stores → submit ratings

🛠️ Technologies Used

Python

FastAPI

Streamlit

MySQL

SQLAlchemy ORM

Uvicorn

Requests library

📌 Notes

Ensure MySQL server is running before launching backend.

Backend must be running before loading the Streamlit frontend.

Update DB credentials correctly to avoid connection issues.

👩‍💻 Author

Priyadharshini Thiyagarajan
Full Stack Python Developer — Store Rating System Project
