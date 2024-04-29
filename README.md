# django-notes-app

<h3>This Django application is deployed on docker container with and without CI/CD process.Using Nginx proxy to deploy and using Jenkins to deploy.</h3>

## Steps:
1. **Launch an EC2 Ubuntu Instance.**
2. **Install Nginx on instance.**
3. **Clone the github repository.**
4. **Install docker on instance.**
5. **Write Dockerfile and build docker image.**
6. **Deploy application on docker container.**
7. **Setup nginx reverse proxy.**
8. **Access the application on proxy url.**

## Project Architecture
<img src="https://github.com/swaleham/django-notes-app/blob/main/NginxProxy.svg">

## Deploying Django Notes App using Jenkins CI/CD
1. **Launch an EC2 Ubuntu Instance.**
2. **Install Jenkins**
3. **Install required plugins.**
4. **Create a declarative pipeline**
5. **Write script to clone,build,push and deploy docker container.**
6. **Run the pipeline**
7. **Terminate the EC2 instance.**
