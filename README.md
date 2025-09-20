# 🌍 Meet in the Middle (Backend)

This is the **backend API** for the **Meet in the Middle** web application. It provides user authentication, midpoint calculation, real-time communication, file uploads, notifications, and integration with Google Maps and payment services.

---

## 🚀 Features

- 🔑 **Authentication & Authorization**
  - JWT-based login & signup
  - OAuth login with Google and Facebook
  - Role-based access control for protected routes

- 📍 **Location & Midpoint Services**
  - Endpoints to calculate the midpoint between addresses
  - Integration with Google Maps API for place suggestions
  - Save and retrieve meeting points



- 📦 **File & Media Management**
  - Upload and manage images using **Cloudinary**
  - Generate PDFs with **PDFKit**
  - Image optimization with **Sharp**

- 🛡 **Security & Optimization**
  - Helmet, HPP, compression, and rate limiting
  - CORS configuration
  - Input validation with **Joi**
---

## 🛠️ Tech Stack

- **Runtime & Framework:** Node.js, Express 5  
- **Database:** MongoDB with Mongoose  
- **Authentication:** JWT, Passport (Google, Facebook)  
- **Real-time:** Socket.io  
- **File Management:** Multer, Cloudinary, Sharp  
- **Payments:** Stripe  
- **Scheduling:** node-cron, node-schedule  
- **Validation:** Joi  
- **Utilities:** Moment.js, UUID, ExcelJS, PDFKit  
- **Security:** Helmet, HPP, CORS, Express Rate Limit  
- **API Docs:** Swagger-jsdoc, Swagger-UI-Express  

---


```bash
git clone https://github.com/YourUsername/MeetInTheMiddle-Backend
cd mtm-server
