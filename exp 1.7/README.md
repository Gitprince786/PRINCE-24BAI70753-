# Experiment 1.7

This project contains a Spring Boot backend and a React/Vite frontend.

## Run the backend

Set `JWT_SECRET` to a strong signing secret and `AES_SECRET` to a 16-, 24-, or
32-character AES key in the backend process environment. Then run:

```bash
cd backend
mvn spring-boot:run
```

The backend seeds demo accounts `admin` / `admin123` and `user` / `user123`.
Do not use these accounts outside local development.

## Run the frontend

In another terminal:

```bash
cd frontend
npm install
npm run dev
```
