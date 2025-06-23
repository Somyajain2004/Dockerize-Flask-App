# Dockerize-Flask-App

This is a simple Flask app containerized using Docker.

## Run Instructions


first, Clone the repo, then run in terminal the following commands :  

```bash
# Build Docker image
docker build -t flask-docker-app .
```
```
# Run Docker container
docker run -d -p 5000:5000 flask-docker-app
```
