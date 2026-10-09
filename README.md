# SkillForge Backend
Requirements: Java 17+ and Maven.

Run from this folder:
```bash
mvn spring-boot:run
```
API endpoints:
- POST `http://localhost:8080/api/auth/register` with `{"name":"Demo User","email":"demo@example.com","password":"password123"}`
- POST `http://localhost:8080/api/auth/login` with `{"email":"demo@example.com","password":"password123"}`

Local users are stored in an H2 database file under `data/`.
