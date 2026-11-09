# Madaba Transport System

## Structure
- `frontend/` — Next.js 16, React 19, TypeScript, Tailwind CSS 4
- `backend/` — Spring Boot 4, Java 21, Maven, PostgreSQL

## Run frontend
```
cd frontend
npm install
npm run dev
```

## Run backend
1. Create a PostgreSQL database named `Madaba-Transport`.
2. Copy `backend/src/main/resources/application-local.properties.example` to `application-local.properties` and set real values.
3. Start:
```
cd backend
mvn spring-boot:run
```
API runs on `http://localhost:8080`.
