asmi26

A simple Django project containerized with Docker and deployed using Jenkins.

Project Structure
asmi26/
│-- app1/
│-- app2/
│-- Dockerfile
│-- Jenkinsfile
│-- docker-compose.yml
│-- requirements.txt
│-- manage.py

Prerequisites

Docker & Docker Compose installed

Jenkins installed (for CI/CD pipeline)

Docker Hub account (for pushing images)

Setup & Run

1. Clone the Repository
git clone <repository-url>
cd StudentProject

2. Build and Run with Docker Compose
docker-compose up --build


3. Access the Application
The Django app will be running at: http://localhost:8000/

CI/CD with Jenkins

1. Configure Jenkins Pipeline

Add a new Jenkins pipeline.

Set up Jenkins to use the Jenkinsfile in the repository.

2. Run the Pipeline

The pipeline will build, test, and push the Docker image to Docker Hub.

Stopping the Application

To stop the running containers, use:
docker-compose down
