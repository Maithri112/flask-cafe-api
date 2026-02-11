# ☕ Flask Cafe REST API

## 📌 Overview
This project is a RESTful API built using Flask that manages cafe data including location, amenities, and pricing details.

The API allows users to retrieve, add, update, and delete cafe records through structured HTTP endpoints. It demonstrates backend development and database management concepts.

## 🛠 Tech Stack
- Python
- Flask
- Flask-SQLAlchemy
- SQLite
- REST API Architecture
- Environment Variables

## ⚙️ Features
- Retrieve all cafes
- Search cafes by location
- Add new cafe entries
- Update cafe pricing
- Delete cafe records
- JSON-based API responses
- Database integration using SQLAlchemy
- Secure configuration using environment variables

## 🚀 API Endpoints

### GET All Cafes
```
/all
```

### GET Random Cafe
```
/random
```

### Search Cafe by Location
```
/search?loc=London
```

### Add New Cafe
```
/add
```

### Update Cafe Price
```
/update-price/<cafe_id>
```

### Delete Cafe
```
/report-closed/<cafe_id>
```

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/flask-cafe-api.git
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Create `.env` File
```
SECRET_KEY=your_secret_key
DATABASE_URL=your_database_url
```

### 4️⃣ Run the Application
```bash
python main.py
```

Visit:
```
http://127.0.0.1:5000
```

## 📊 Skills Demonstrated
- REST API Development
- HTTP Methods (GET, POST, PATCH, DELETE)
- Database Integration
- JSON Handling
- Backend Architecture
- CRUD Operations
- Secure Configuration Management

## 🎯 Real-World Use Case
This API structure can be extended for:
- Restaurant management systems
- Location-based services
- Data-driven web applications
