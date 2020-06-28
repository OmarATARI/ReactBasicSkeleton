## Stack

MERN stack for development (Mongo, Express, ReactJs, Node). Nginx for production build.


## Getting Started

```
docker-compose up --build -d
```
- Front (UI): http://localhost:3000
- A simple endpoint listing users (API): http://localhost:8080/users

## Build for production (UI & ReactJs)

- replace Dockerfile content by Dockerfile_prod in ui folder
- replace ui port service to 80 in docker-compose.yml
