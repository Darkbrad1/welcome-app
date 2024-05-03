# ShortProject2: Welcome App

# Overview
The objective of this project is to build a straightforward web application using Python and Django, and then deploy it on Tomcat within Docker containers. This deployment process will be automated using a Jenkins pipeline.


# Prerequisites
1. Python 3.12 and Django installed
2. Docker installed
3. Git installed
4. Jenkins installed and configured


# Steps to run Locally
1. Clone the Repository
   - git clone https://github.com/Darkbrad1/welcome-app.git

2. Navigate to project folder
   - cd welcome-app

3. Install Python dependencies
   - pip install -r requirements.txt

4. Run Django development server
   - python manage.py runserver

5. Access the Web Application:
   - Open your web browser and go to http://localhost:8000


# Jenkins Pipeline Configuration
The Jenkins pipeline automates the build and deployment process of the web application using Docker containers.

Pipeline Stages
- Checkout:Checks out the code from the Git repository.
- Build Docker Image: Builds the Docker image for the web application.
- Push Docker Image: Pushes the Docker image to a Docker registry.



# Contributors
- Bradley Andrews
