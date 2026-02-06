# AI-Resume-Builder 

AI-Resume-Builder is a powerful backend service for automated resume generation.
Built with Spring Boot, OpenAI API, and MySQL, it provides secure and scalable APIs to generate recruiter-ready resumes using advanced AI models.

# Tech Stack
Component	Technology
Backend	Spring Boot
Security	Spring Security + JWT
AI Model	OpenAI GPT-3.5 / GPT-4 API
Database	MySQL
ORM	Spring Data JPA
Build Tool	Maven
```
📂 Project Structure
Code
src/main/java/com/ai/resume/builder
│
├── controller
│   └── ResumeController.java
│
├── service
│   └── ResumeService.java
│
├── repository
│   ├── ResumeRepository.java
│   └── UserRepository.java
│
├── model
│   └── Resume.java
│
└── ResumeBuilderApplication.java
```
▶️ How to Run
Clone the repository

bash
git clone https://github.com/YOUR_USERNAME/AI-Resume-Builder.git
cd resume-ai-backend
Install dependencies

bash
mvn clean install
Run the project

bash
mvn spring-boot:run
Access the backend

Code
http://localhost:8080
🔒 Security
Authentication handled via Spring Security

JWT-based token system for secure API access

🌟 Features
AI-powered resume generation using OpenAI GPT models

Secure user authentication and authorization

MySQL database integration for storing resumes and user data

RESTful APIs for seamless integration with frontend applications
