# Dockerized Flask App

A simple Python Flask web application containerized with Docker.

## Technologies
- Python
- Flask
- Docker

## Project Structure
- `dev.py` - main Flask app
- `requirements.txt` - dependencies
- `Dockerfile` - container setup

## How to Run
```bash
docker build -t mydevapp .
docker run -p 5000:5000 mydevapp


Then open:
http://localhost:5000

Purpose

This project was built to practice containerizing a Python application using Docker.






