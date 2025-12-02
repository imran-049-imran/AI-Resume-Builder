# AI-Resume-Builder

A powerful AI-based Resume Generation backend built using Spring Boot, OpenAI API, and MySQL.
This backend provides secure APIs.

# Tech Stack

Component	   Technology
Backend     Framework	Spring Boot
Security	  Spring Security + JWT
AI Model	  OpenAI GPT-3.5 / GPT-4 API
Database	  MySQL
ORM	        Spring Data JPA
Build Tool	Maven

```
Backend (Spring Boot) – Project Structure
src/main/java/com/ai/resume/builder
│
├── controller
│   ├── ResumeController.java
│
├── service
│   ├── ResumeService.java
│   
├── repository
│   ├── ResumeRepository.java
│   ├── UserRepository.java
│
├── model
│   ├── Resume.java
│
│
└── ResumeBuilderApplication.java
```

▶️ How to Run
1️⃣ Clone the repository
git clone https://github.com/YOUR_USERNAME/AI-Resume-Builder.git
cd resume-ai-backend

2️⃣ Install dependencies
mvn clean install

3️⃣ Run the project
mvn spring-boot:run

4️⃣ Backend starts at:
http://localhost:8080
