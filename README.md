# GreenSwap API 🌱  
*Trade sustainably, save the planet.*  

GreenSwap is a **RESTful API** built with **Spring Boot** that powers a community marketplace for trading eco-friendly products. It enables users to swap reusable goods, track carbon savings, and promote sustainable living.

---

## 🚀 Key Features  
✅ **User Authentication**  
- JWT-based secure registration/login  
- Role-based access (Users & Admins)  

🛒 **Product Marketplace**  
- Create/list eco-friendly products  
- Categories: Reusables, Organic, Upcycled  
- Image uploads (max 3 per product)  

🔄 **Trading System**  
- Propose swaps ("My bamboo straws for your vegan soap")  
- Accept/reject trade requests  
- Trade history tracking  

🌱 **Sustainability Metrics**  
- CO₂ savings calculator per trade  
- Personal environmental impact dashboard  

📊 **Admin Analytics**  
- Top traded products  
- Category breakdowns  
- User activity reports  

---

## 💻 Tech Stack  
**Backend**  
- Java 17 + Spring Boot 3.x  
- Spring Security + JWT  
- Hibernate + PostgreSQL  
- MapStruct for DTOs  

**DevOps**  
- Dockerized deployment  
- Swagger/OpenAPI documentation  
- GitHub Actions CI/CD  

---

## 🛠️ Setup & Run  
1. **Prerequisites**  
   - Java 17, Docker, PostgreSQL

2. **Run with Docker**  
   ```bash
   docker-compose up --build
