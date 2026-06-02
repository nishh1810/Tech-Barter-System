🚀 Tech Barter System – Microservices E-Commerce Platform
📌 Overview
Tech Barter System is a scalable, distributed e-commerce platform built using Spring Boot microservices architecture for the backend and Flutter for cross-platform frontend applications.
The system supports multiple user roles (User, Seller, Admin), each with dedicated applications, all connected through a centralized API Gateway.
It is designed to demonstrate real-world system design, microservices communication, role-based access control, and multi-client architecture.

🧠 System Architecture

The platform follows a microservices-based distributed architecture:

Independent backend services for each domain
Central API Gateway for request routing and authentication
Separate Flutter applications for each user role
🧩 Backend Services (Spring Boot)
API Gateway – Entry point for all requests, handles routing, authentication, and request filtering
Auth Service – Manages user authentication and JWT-based authorization
Seller Service – Handles seller accounts, product listings, and inventory management
User/Marketplace Service – Manages product browsing and customer interactions
Admin Service – Provides administrative control over users, sellers, and platform data
📱 Frontend Applications (Flutter)
User App – Customers can browse products, view listings, and interact with sellers
Seller App – Sellers can manage products, inventory, and listings
Admin App – Admin dashboard for monitoring users, sellers, and system activity
⚙️ Tech Stack

Backend: Java, Spring Boot, REST APIs
Architecture: Microservices, API Gateway, JWT Authentication
Frontend: Flutter 
Databases: MongoDB, MySQL
DevOps Tools: Docker, Git, CI/CD pipelines
Other Tools: Postman, GitHub, Maven

🔗 Demo

👉 https://youtu.be/mSk80W7WKCo

📦 Repositories

🔐 API Gateway – https://github.com/nishh1810/TechBarter_Gateway
🛒 Seller Service – https://github.com/nishh1810/TechBarter_Seller
🧑‍💼 Admin Service – https://github.com/nishh1810/TechBarter_Admin
🧑‍💻 User Service – https://github.com/nishh1810/TechBarter

This system is organized into multiple services:

🔐 API Gateway – Central routing and request handling
👤 Auth Service – Authentication and authorization
🛒 Seller Service – Product and seller management
🧑‍💻 User Service – Marketplace and product browsing
🧑‍💼 Admin Service – Platform monitoring and control
📱 Flutter Apps – User, Seller, and Admin applications

👉 Main Repository: Tech-Barter-System (This Repo)

✨ Key Features
🔐 Secure JWT-based authentication system
🧩 Microservices architecture for scalability and modularity
📱 Cross-platform mobile applications using Flutter
🛒 Product listing and seller management system
👨‍💼 Admin control panel for platform monitoring
⚡ API Gateway for centralized request handling
🚀 CI/CD deployment pipeline for automated delivery
🧑‍💻 My Role
Designed and developed backend microservices using Spring Boot
Implemented REST APIs for authentication, seller, and user services
Built and integrated API Gateway for routing and security
Developed Flutter frontend applications for multiple user roles
Worked in a team of 4 using Agile methodology and Git workflows
🧪 System Design Highlights
API Gateway pattern for centralized request management
Independent microservices for each domain
Role-based architecture (User, Seller, Admin)
Stateless authentication using JWT
Scalable backend design supporting distributed services
📸 Screenshots
User App Home Screen
<img width="1238" height="594" alt="image" src="https://github.com/user-attachments/assets/ed788f35-3cbf-4566-8ed1-050104cd49e4" />
Seller Dashboard
<img width="1234" height="574" alt="image" src="https://github.com/user-attachments/assets/58646a22-a10c-4dea-aa7a-42a3f859a87d" />
Admin Panel
<img width="1223" height="600" alt="image" src="https://github.com/user-attachments/assets/20ad37a7-6477-4ae6-86ce-a0375f99004c" />
