# Restful Booker API Testing using Postman

A complete API testing project for the **Restful Booker API** using **Postman**. This project demonstrates end-to-end testing of RESTful APIs including Authentication, CRUD operations, response validation, and API health checks.

---

##  Project Overview

The objective of this project is to validate the functionality of the Restful Booker API by testing all major endpoints using Postman.

The collection includes request validation, response verification, status code assertions, and reusable environment variables.

---

## 🚀 Technologies Used

- Postman
- REST API
- JSON

---

## 📂 Project Structure

```
Restful-Booker-API-Testing/
│
├── README.md
└── screenshots/
    ├── auth.png
    ├── create-booking.png
    ├── get-booking.png
    ├── update-booking.png
    ├── partial-update.png
    ├── delete-booking.png
    └── health-check.png
```

---

## 🔗 Base URL

```
https://restful-booker.herokuapp.com
```

---

# API Endpoints Tested

| Method | Endpoint | Status |
|---------|----------|--------|
| POST | /auth | ✅ |
| GET | /booking | ✅ |
| GET | /booking/{id} | ✅ |
| POST | /booking | ✅ |
| PUT | /booking/{id} | ✅ |
| PATCH | /booking/{id} | ✅ |
| DELETE | /booking/{id} | ✅ |
| GET | /ping | ✅ |

---

# Test Scenarios

### Authentication

- Generate Authentication Token
- Verify Status Code
- Validate Response Body
- Store Token

---

### Create Booking

- Create New Booking
- Validate Status Code
- Validate Booking ID
- Validate Response Body

---

### Get Booking IDs

- Retrieve All Booking IDs
- Verify Response Time
- Verify Response Format

---

### Get Booking

- Retrieve Booking by ID
- Verify Booking Details
- Verify Response Structure

---

### Update Booking

- Update Existing Booking
- Validate Updated Data
- Verify Status Code

---

### Partial Update

- Update Selected Fields
- Verify Updated Information
- Validate Response

---

### Delete Booking

- Delete Existing Booking
- Verify Successful Deletion

---

### Health Check

- Verify API Availability
- Validate Server Response

---

# Response Validation

The project validates:

- HTTP Status Codes
- Response Body
- Response Time
- JSON Structure
- Booking ID Generation
- Authentication Token
- CRUD Operations

---

# Environment Variables

| Variable | Description |
|----------|-------------|
| baseUrl | API Base URL |
| username | Admin Username |
| password | Admin Password |
| token | Authentication Token |
| bookingid | Booking ID |

---

# Screenshots

Screenshots of my successful requests inside the `screenshots` folder.

Example:

- Authentication
- Create Booking
- Get Booking
- Update Booking
- Delete Booking
- Health Check

---

# Future Improvements

- Newman Integration
- GitHub Actions
- HTML Reports
- Data Driven Testing
- CI/CD Pipeline
