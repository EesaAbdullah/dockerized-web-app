# Dockerized Web Application

This project demonstrates how to containerize a simple
Python Flask application using Docker.

## Steps to Run
1. Build Docker image
   docker build -t docker-web-app .

2. Run Docker container
   docker run -p 5000:5000 docker-web-app

3. Access application
   http://localhost:5000

## Tools Used
- Docker
- Python
- Flask

## Goal
Learn containerization fundamentals for DevOps.
