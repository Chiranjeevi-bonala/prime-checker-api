#  Prime Checker API – Backend Challenge (Python + FastAPI)

This project is a simple API built with **Python** and **FastAPI** that checks whether a given number is a prime number.

---

## ✅ Features

- Accepts a number as a query parameter.
- Returns a JSON response indicating whether it is prime.
- Handles invalid inputs gracefully.
- Provides Swagger UI for easy testing.

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Framework**: FastAPI
- **Server**: Uvicorn (ASGI server)

---

## 📁 Project Structure
prime-checker-api/
│
├── main.py # Main FastAPI application
├── README.md # Project documentation (this file)

---

## 🚀 How to Run Locally

1. Install dependencies
```bash
pip install fastapi uvicorn
2. Run the FastAPI server
bash
Copy
Edit
uvicorn main:app --reload
3️. Open in browser
Go to:

arduino
Copy
Edit
http://127.0.0.1:8000/docs
You’ll see Swagger UI where you can test the API.


