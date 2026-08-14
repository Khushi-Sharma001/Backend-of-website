# Backend of Website

A REST API backend developed using **Python, FastAPI, and MySQL** for a travel website. The backend handles customer bookings, destinations, and 
vehicle information through structured API endpoints.

## 🚀 Features

* Customer booking management
* Create, read, update, and delete bookings
* Destination management
* Vehicle information management
* MySQL database integration
* RESTful API architecture
* Interactive API documentation using Swagger UI
* Input validation using Pydantic

## 🛠️ Technologies Used

* **Python**
* **FastAPI**
* **MySQL**
* **Pydantic**
* **Uvicorn**
* **REST APIs**

## 📂 Project Structure

```text
backend/
│
├── main.py
├── database.py
│
└── routers/
    ├── bookings.py
    ├── destinations.py
    └── vehicles.py
```

## 🔗 API Endpoints

### Bookings

| Method | Endpoint         | Description            |
| ------ | ---------------- | ---------------------- |
| GET    | `/bookings`      | Get all bookings       |
| GET    | `/bookings/{id}` | Get a specific booking |
| POST   | `/bookings`      | Create a new booking   |
| PUT    | `/bookings/{id}` | Update a booking       |
| DELETE | `/bookings/{id}` | Delete a booking       |

### Destinations

| Method | Endpoint             | Description                |
| ------ | -------------------- | -------------------------- |
| GET    | `/destinations`      | Get all destinations       |
| GET    | `/destinations/{id}` | Get a specific destination |
| POST   | `/destinations`      | Create a destination       |

### Vehicles

Vehicle APIs are implemented to manage vehicle information, including vehicle details and availability.

## 🗄️ Database

The backend uses **MySQL** to store and manage application data.

Main database tables include:
│
├── bookings
├── destinations
└── vehicle


## 🎯 Project Objective

The objective of this project was to build a functional backend for a travel website that can handle bookings and manage destination and vehicle information
through RESTful APIs.

## 👩‍💻 Author

**Khushi Sharma**
