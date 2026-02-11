# MyComputerSeekho.com


**ComputerSeekho** is a full-stack educational institute management platform designed to handle
student enquiries, course management, admissions, payments, placements, and administrative workflows.

The system provides secure, role-based access for admins, staff, and students, enabling end-to-end
management of an institute’s operations through modern web technologies.


## 📁 Project Structure

MyComputerSeekho.com/
│
├── ComputerSeekho/ # Java Spring Boot Backend
├── ComputerSeekho.Net/ # ASP.NET Core Backend (Entity Framework)
├── computer-seekho-frontend/ # React Frontend (Vite)
├── Dump20260204.sql # Database dump
├── .gitignore
└── README.md


---

## 🧩 Tech Stack

### Backend (Java)
- Java
- Spring Boot
- Spring Security (JWT)
- JPA / Hibernate
- MySQL
- Maven

### Backend (.NET)
- ASP.NET Core
- Entity Framework Core
- REST APIs
- JWT Authentication

### Frontend
- React
- Vite
- JavaScript
- Context API
- CSS

### Database
- MySQL
- SQL Dump included

---

## ⚙️ How to Run the Project

### 1️⃣ Java Spring Boot Backend
```bash
cd ComputerSeekho
./mvnw spring-boot:run
Runs on default Spring Boot port (e.g. 8080).

2️⃣ ASP.NET Core Backend
cd ComputerSeekho.Net/ComputerSeekho.Net
dotnet run
Runs on configured ASP.NET port.

3️⃣ React Frontend
cd computer-seekho-frontend
npm install
npm run dev
Runs on http://localhost:5173

4️⃣ Database
Import Dump20260204.sql into MySQL

Update DB credentials in:

application.properties (Spring Boot)

appsettings.json (.NET)

🔐 Features
Role-based authentication (Admin / Staff / Student)

Enquiry & Follow-up management

Course & Batch management

Payments & Placements

Image uploads

Multi-language support

Secure APIs with JWT
