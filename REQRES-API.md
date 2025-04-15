# ReqRes API Documentation

This documentation provides the details of API interactions with the [ReqRes](https://reqres.in) API.

## 📋 API Overview
ReqRes provides a free fake online REST API for testing and prototyping. We can simulate different HTTP methods (GET, POST, PUT, DELETE) and perform CRUD operations on a set of fake users.

### Base URL:

---

## 1️⃣ **GET /users/{id}**

### **Description**:
Retrieve a user’s details by their `id`.

### **Request Example**:
DELETE https://reqres.in/api/users/2
POST https://reqres.in/api/users
{
  "name": "Vishal",
  "job": "Tech Writer"
}
{
  "name": "Vishal",
  "job": "Tech Writer",
  "id": "1234",
  "createdAt": "2025-04-12T09:13:33.123Z"
}
PUT https://reqres.in/api/users/2
{
  "name": "Vishal",
  "job": "Tech Writer"
}
{
  "name": "Vishal",
  "job": "Tech Writer",
  "updatedAt": "2025-04-12T09:20:12.456Z"
}
