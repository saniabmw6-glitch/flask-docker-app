# Flask Task Tracker (Dockerized)

A simple Task Tracker web app built with Flask, containerized with Docker, and deployed on an AWS EC2 instance.

## Tech Stack
Python Flask, Docker, Docker Compose, AWS EC2 (Ubuntu), Git

## Architecture
Browser -> AWS EC2 (Port 5000) -> Docker Container -> Flask App

## Run Locally
```bash
git clone https://github.com/saniabmw6-glitch/flask-docker-app.git
cd flask-docker-app
docker compose up --build
```
Open: http://localhost:5000

## Challenges and Solutions
- Docker permission error: added the user to the docker group
- File not found in container: fixed a filename with a trailing space
- App not reachable: bound Flask to 0.0.0.0 and opened port 5000 in the Security Group

## Key Learnings
Writing a Dockerfile, Docker Compose, port mapping, non-root containers, and cloud deployment.

## Screenshots
Screenshots will be added here.
