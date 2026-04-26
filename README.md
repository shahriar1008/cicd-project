# CI/CD Project

Simple Node.js application for learning CI/CD pipeline with Docker and GitHub Actions.

## Run locally
npm install
node app.js

## Docker
docker build -t cicd-app .
docker run -p 3000:3000 cicd-app
