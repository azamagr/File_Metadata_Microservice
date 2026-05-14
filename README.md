# 📁 File Metadata Microservice

This project is part of the FreeCodeCamp APIs and Microservices certification.

It is a simple full-stack JavaScript application that allows users to upload a file and receive metadata about it, such as:

- File name
- File type
- File size

---

## 🚀 Live Demo

👉 Click here to view live project:  
https://caa5e0d1-f233-43d4-abb8-d25ea1133494-00-yir76p0skqx1.sisko.replit.dev/

---

## 📌 Project Description

This project fulfills the requirements of the **File Metadata Microservice** from FreeCodeCamp. The main goal is to handle file uploads using `multer` and return JSON metadata.

---

## ⚙️ Technologies Used

- Node.js
- Express.js
- Multer
- JavaScript (ES6)
- HTML / CSS (optional frontend)

---

## 📂 API Endpoint

### POST `/api/fileanalyse`

Upload a file and receive metadata response.

#### Response Example:
```json
{
  "name": "example.png",
  "type": "image/png",
  "size": 23056
}
