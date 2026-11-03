# Full Stack Development 2

This repository contains coursework experiments for Full Stack Development 2. Each experiment is kept in its own folder so its frontend, backend, and supporting files remain organized.

## Experiments

| Folder | Project |
| --- | --- |
| `exp 1.1` | React post composer |
| `exp 1.2` | Posts workspace using React, Vite, and Redux Toolkit |
| `exp 1.3` | Role-based authentication with protected routes |
| `exp 1.4` | Calendar and event management app |
| `exp 1.5` | Post management system with React and Spring Boot |
| `exp 1.6` | Student task manager with frontend and backend |
| `exp 1.7` | Full-stack application with a Spring Boot backend and React/Vite frontend |
| `exp 1.8` | Full-stack experiment with frontend, backend, and Docker Compose |
| `exp 1.9` | CI/CD pipeline demo with automated tests, Docker, and canary deployment |

## Run Experiment 1.9

### Frontend

Requires Node.js and npm.

```bash
cd "exp 1.9/frontend"
npm install
npm run dev
```

Open the local address printed by Vite.

### Backend containers

Requires Docker with the Compose plugin.

```bash
cd "exp 1.9"
docker compose up --build
```

The primary backend is published on port `8080`; the canary backend is published on port `8082`. Stop the containers with `Ctrl+C`, or run `docker compose down` from the same directory.

### Backend tests

Requires Java 17. On Windows, use `mvnw.cmd`; on macOS/Linux, use `./mvnw`.

```powershell
cd "exp 1.9/backend"
mvnw.cmd test
```

```bash
cd "exp 1.9/backend"
./mvnw test
```

## Technologies

The experiments use a mix of React, Vite, Redux Toolkit, React Router, JavaScript, Java, Spring Boot, Maven, and Docker Compose. Check an experiment's own folder for its dependencies and setup details.
