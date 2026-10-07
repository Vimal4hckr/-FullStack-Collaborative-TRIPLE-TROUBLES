# 🛒 SmartCart – AI-Powered Full-Stack E-Commerce Platform

## 📌 Project Status
🚧 **In Active Development (Phase 2: Architecture & Schema Design)**

## 📖 About the Project
SmartCart is an enterprise-grade, full-stack e-commerce web application engineered as a milestone B.Tech project. Beyond standard e-commerce workflows, SmartCart integrates machine learning microservices to deliver personalized product recommendations, customer sentiment analytics, and predictive sales forecasting, bridging robust software engineering with practical Data Science.

## 🎯 Objectives
* **Production-Grade Engineering:** Build a decoupled, scalable multi-tier architecture using React.js and Spring Boot.
* **AI/ML Integration:** Embed data-driven microservices for predictive analytics and real-time recommendations.
* **Secure Token-Based Auth:** Implement modern stateless security protocols for access delegation.
* **Relational Data Modeling:** Design a normalized MySQL database optimized for high-concurrency read/write operations.
* **DevOps Lifecycle:** Containerize the ecosystem for seamless, platform-agnostic deployment.

## 🛠️ Technologies & Infrastructure

### Frontend
* **Core:** HTML5, Modern JavaScript (ES6+), React.js (v18+)
* **State Management:** Redux Toolkit / Context API
* **Styling:** Tailwind CSS & Shadcn/ui (for responsive, atomic UI components)

### Backend (Monolith & Microservices)
* **Primary Framework:** Java / Spring Boot (RESTful API Ecosystem)
* **Security:** Spring Security & JSON Web Tokens (JWT)
* **AI/ML Engine:** Python / Flask or FastAPI (Scikit-Learn, NLTK / Transformers)
* **Data Access:** Spring Data JPA (Hibernate)

### Database & Storage
* **Relational DB:** MySQL (v8.0)
* **Caching Layer:** Redis (for session data and frequent product queries)
* **Object Storage:** Cloudinary API / AWS S3 (for dynamic product image hosting)

### DevOps & Tools
* **Containerization:** Docker & Docker Compose
* **API Testing & Documentation:** Postman / OpenAPI Swagger UI
* **Build Tools:** Maven (Java), npm (JavaScript)
* **Version Control:** Git & GitHub

## 👥 Advanced User Features

### 🛍️ Core E-Commerce
* **Stateless Authentication:** Secure registration, login, and token refresh cycles via JWT.
* **Dynamic Catalog Nav:** Multi-attribute filtering (price, brand, rating) and instant search.
* **Persistent Cart & Wishlist:** Database-backed state management across user sessions.
* **Simulated Checkout Flow:** Sandbox payment gateway integration ([Stripe](https://stripe.com) / [Razorpay](https://razorpay.com)).
* **Automated Invoice Engine:** Instant, server-generated transactional PDF receipts upon successful payment.

### 🧠 Data Science & Smart Features
* **Personalized Recommendation Engine:** Hybrid collaborative and content-based recommendation carousel (*"Frequently Bought Together"*).
* **Review Sentiment Analysis:** Natural Language Processing (NLP) pipeline running on reviews to tag feedback as Positive, Neutral, or Negative, giving users a quick summary metric.

## 👨‍💼 Admin & Intelligence Features
* **Secure RBAC:** Role-Based Access Control restricting system configurations to verified administrators.
* **Inventory Control & Alerts:** Real-time stock tracking with automated low-inventory webhooks.
* **Product & Category CRUD:** Comprehensive management of store catalogs with dynamic image uploading.
* **AI Sales Forecasting Dashboard:** Time-series forecasting (e.g., ARIMA or Linear Regression models) visualizing projected sales trends for the upcoming month based on historical data.

## 🏗️ Technical Architecture
```text
┌─────────────────┐       ┌───────────────────────────┐       ┌────────────────┐
│    Frontend     │ ────> │      Backend Engine       │ ────> │  Database Tier │
│ (React/Tailwind)│ <──── │ (Spring Boot REST API)    │ <──── │    (MySQL)     │
└─────────────────┘       └─────────────┬─────────────┘       └────────────────┘
                                        │ (REST/HTTP)
                                        ▼
                          ┌───────────────────────────┐
                          │   AI/ML Microservice      │
                          │   (Python / FastAPI)      │
                          └───────────────────────────┘
```

## 📂 System Architecture Blueprint
```text
smartcart-ecosystem/
├── smartcart-frontend/          # React.js SPA (UI components, Redux state)
├── smartcart-backend/           # Spring Boot application (Controllers, Services, Security)
├── smartcart-ml-service/        # Python service (Sentiment analysis, Sales forecasting model)
└── docker-compose.yml           # Multi-container orchestration config
```

## 🚀 Development Progress
- [x] High-level architecture & tech stack finalized
- [ ] Database normalization and ERD design
- [ ] UI wireframing & component system planning
- [ ] Spring Security & JWT setup
- [ ] Core REST API endpoint development (Product/User CRUD)
- [ ] Python ML microservice implementation
- [ ] Cross-service API integration
- [ ] Component rendering and state connection on Frontend
- [ ] Integration testing & containerization (Docker)
- [ ] Cloud staging deployment

## 👩‍💻 Developer
**Swathilakshmi V**  
*B.Tech – Artificial Intelligence & Data Science*  

## 👨‍🏫 Project Guidance
Developed under the guidance of my academic mentor.
