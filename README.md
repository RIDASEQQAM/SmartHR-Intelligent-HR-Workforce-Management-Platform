# SmartHR – Intelligent HR & Workforce Management Platform

SmartHR is a full-stack enterprise HR management platform built with Java 17, Spring Boot 3, Angular 17, and PostgreSQL.  
It provides a complete ecosystem for managing employees, attendance, leave workflows, and performance evaluations with clean architecture and production-ready design.

This project is designed to demonstrate real-world enterprise architecture and full-stack development skills that are highly valuable in the industry.

---

## Features

### Authentication & Security
- JWT authentication
- Role-based access control (Admin, HR, Manager, Employee)
- Secure password encryption
- Angular route guards and interceptors

### Employee Management
- Employee CRUD operations
- Department and position assignments
- Search, filter and pagination
- Export to CSV or PDF

### Attendance Tracking
- Check-In / Check-Out system
- Daily and monthly summaries
- Team attendance dashboard for managers

### Leave Management
- Submit leave requests
- Multi-step approval workflow (Employee → Manager → HR)
- Leave history per employee
- Email or in-app notifications

### Performance Evaluation
- KPI definitions
- Employee self-evaluations
- Manager evaluations
- Performance scoring and detailed history

### Dashboards & Analytics
- Summary KPIs (employees, attendance rate, pending leaves, performance)
- Charts and visual insights
- Department distribution metrics

### Admin Panel
- User and role management
- KPI configuration
- System logs and audit tracking
- Leave policy settings

---

## System Architecture

### Backend (Spring Boot)
- Java 17 / Spring Boot 3
- Spring Security + JWT
- Spring Data JPA
- PostgreSQL
- MapStruct for DTO mapping
- Global exception handling
- Swagger / OpenAPI documentation

### Frontend (Angular 17)
- Standalone components
- Angular Material or TailwindCSS
- Reactive forms
- Shared reusable components
- Charts with ApexCharts or Ng2-Charts

### Infrastructure
- Docker / Docker Compose
- GitHub Actions or GitLab CI/CD
- Nginx reverse proxy (optional)

---

## Tech Stack

### Backend
- Java 17  
- Spring Boot 3  
- Spring Security  
- Spring Data JPA  
- PostgreSQL  
- Maven  

### Frontend
- Angular 17  
- TypeScript  
- Angular Material or TailwindCSS  

### DevOps
- Docker  
- Docker Compose  
- Git / GitHub / GitLab CI  

---

## Database Schema (Main Tables)

- users  
- roles  
- employees  
- departments  
- attendance_records  
- leave_requests  
- performance_reviews  
- kpi_definitions  
- audit_logs  

---

## Testing

### Backend Testing
- JUnit 5  
- Mockito  
- Spring Boot Test  
- Testcontainers (optional)

### Frontend Testing
- Jasmine / Karma  
- Cypress (optional for E2E)

---

## Running the Project

### Backend
```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### Frontend
```bash
cd frontend
npm install
ng serve
```

### Docker (Full App)
```bash
docker-compose up --build
```

---

## Why SmartHR Is Impressive for Recruiters

This project demonstrates:
- Enterprise-level full-stack development
- Modern security implementation (JWT, RBAC)
- Workflow automation and business logic modeling
- Clean architecture and modular design
- CI/CD and Dockerization
- Rich UI with charts, dashboards, and analytics
- Experience with real-world HR and internal systems

This makes the project suitable for roles in banking, fintech, SaaS, enterprise IT, consulting, HR tech, and corporate environments.

---

## Author

Rida Seqqam  
Full-Stack Java / Spring Boot / Angular Engineer  
LinkedIn: [https://www.linkedin.com/in/rida-seqqam/]

---

## License

MIT License
