# ThinkInPatterns

## Web-based platform for learning software design patterns

ThinkInPatterns is an interactive educational platform designed to teach software design patterns through structured learning, AI-powered testing, and practical feedback.

The platform focuses on the three main categories of design patterns:
- Creational Patterns
- Structural Patterns
- Behavioral Patterns

The goal is to provide a more engaging learning experience compared to traditional methods by combining theoretical content with dynamic assessments and personalized feedback.

---

# Features

- Structured learning modules with a chronological chapter progression
- AI-generated tests with conceptual, practical, and code-based questions
- Real-time evaluation and personalized feedback
- User progress tracking at course and chapter levels
- Hybrid assessment system combining AI evaluation and administrator review
- Anti-abuse mechanism with cooldown periods after repeated failed attempts
- Automated certificate generation after completing the final exam with the required score

---

# Technologies Used

## Backend
- C#
- ASP.NET Core MVC
- Entity Framework Core
- Microsoft SQL Server

## Frontend
- HTML
- CSS
- JavaScript

## AI Integration
- Groq API
- Llama Large Language Model

## Tools
- Docker Desktop
- Visual Studio
- Git & GitHub

---

# Architecture

The project follows **Clean Architecture** principles combined with **Domain-Driven Design (DDD)** to keep business logic independent from external technologies.

The solution is divided into four main layers:

### Domain
- Contains core business logic
- Entities and domain rules

### Application
- Implements application use cases
- Uses CQRS pattern with MediatR

### Infrastructure
- Handles external services:
  - Database access
  - AI communication
  - Authentication services

### Web (Presentation)
- User interface
- Controllers and Razor Views

---

# AI Integration

AI is used to create a dynamic learning experience.

Main AI features:

- Automatic generation of unique questions
- Different question types:
  - Theory
  - Practical scenarios
  - Code-based questions
- AI-based answer evaluation
- Personalized feedback for users

The system uses structured prompts to ensure consistent AI responses and reliable question generation.

---

# Authentication & Authorization

The platform uses:

- ASP.NET Core Identity for user management
- JWT authentication for secure API communication
- Role-based authorization

---

# Database

The application uses Microsoft SQL Server with Entity Framework Core using the Code First approach.
<img width="1065" height="1599" alt="er" src="https://github.com/user-attachments/assets/3be40598-c7c0-4e25-89ac-12813f027074" />


---

# Screenshots

Home Page
<img width="1318" height="604" alt="mainpage1" src="https://github.com/user-attachments/assets/726007d1-496b-40c4-bc60-6d4192f29b42" />
<img width="1453" height="651" alt="mainpage2" src="https://github.com/user-attachments/assets/ba4f1cc9-4a3a-417f-bd1c-1d7c6168402e" />
<img width="1454" height="581" alt="mainpage3" src="https://github.com/user-attachments/assets/4c1e127c-1a3d-4ad1-a314-32a4d5611a47" />

Courses
<img width="1451" height="628" alt="courses" src="https://github.com/user-attachments/assets/75cea288-d0f1-448d-b362-fc9a39553932" />


Register/ Sign in
<img width="1452" height="660" alt="signin" src="https://github.com/user-attachments/assets/0ebce99b-045a-4796-b4fd-819bb7c90e41" />
<img width="1452" height="661" alt="register" src="https://github.com/user-attachments/assets/cd10d3cd-752c-4857-bc4b-cb560588411a" />

Content
<img width="1319" height="635" alt="content" src="https://github.com/user-attachments/assets/bc1900bb-1a13-4f6f-b28e-292be181c818" />
<img width="1319" height="636" alt="testbutton" src="https://github.com/user-attachments/assets/df4d5574-8dfe-4e62-ac82-54f27ed4eb68" />


Tests (Chapter test and Final test)
<img width="1393" height="671" alt="chaptest" src="https://github.com/user-attachments/assets/263b9e00-92ac-494b-a842-c968402adff7" />
<img width="1321" height="603" alt="final" src="https://github.com/user-attachments/assets/6423c802-72e0-4d2a-bf9c-f4a51f758911" />

Graded test
<img width="1380" height="666" alt="graded" src="https://github.com/user-attachments/assets/08116029-88ce-4aa9-a757-1f51544dd51a" />

Admin review
<img width="1570" height="761" alt="adminreview1" src="https://github.com/user-attachments/assets/e324f700-0623-4bff-8c4c-423a0fc6705b" />
<img width="1579" height="761" alt="adminreview2" src="https://github.com/user-attachments/assets/983b8e3b-f13c-49a7-a144-89242f18d950" />

Admin dashboard
<img width="1452" height="662" alt="admin" src="https://github.com/user-attachments/assets/fe2e5f16-5462-496e-80c4-6ef52a8e3cc2" />

Certificate
<img width="1158" height="833" alt="certificate" src="https://github.com/user-attachments/assets/04726810-e99c-41f2-83db-8fb138969add" />

