# Full Stack App with React and a REST API

This project is a Full Stack React application utilizing the [School Database REST API built in a previous project.](https://github.com/alexhippo/rest-api-sql-v3)

Users can use the web interface built with React to:
- sign up
- sign in
- view courses
- create a course (if signed in)
- update their own courses (if authorised)
- delete their own courses (if authorised)

This app was implemented according to the designs specified in the `/mockups` and `/markup` folder.

---

##  CI/CD Implementation

This project includes a CI/CD workflow using **Azure DevOps Pipelines** and **GitHub Actions**.

###  Azure DevOps Pipeline
- Pipeline defined in `azure-pipelines.yml`
- Automated build process triggered on code changes
- Handles installation and build steps for the project

###  GitHub Actions
- Workflow defined in `.github/workflows/test-run.yml`
- Runs automated checks/tests on commits
- Ensures code stability on each push

---

##  Docker & Containerization

This project uses Docker for containerization and environment consistency.

### Docker Setup
- Application containerized using Docker
- `docker-compose.yml` used to manage multi-service setup (API + Client)
- Ensures consistent development and deployment environments

---

##  Motivation
This project was created as part of the [Treehouse Full Stack Javascript Techdegree](https://teamtreehouse.com/techdegree/full-stack-javascript).

It also demonstrates real-world engineering practices including CI/CD automation and containerized application deployment.

---

##  Technologies used
- JavaScript
- Node.js
- Express
- SQLite
- Sequelize (SQL ORM)
- React (React Router, Hooks, Context API)
- Authentication
- Docker
- Docker Compose
- Azure DevOps Pipelines
- GitHub Actions
- Postman

---

## 🏁 Getting started

###  Clone the repository
```bash
git clone https://github.com/WardahFayyaz/fullstack-auth-ci-cd-azure-devops.git
cd fullstack-auth-ci-cd-azure-devops