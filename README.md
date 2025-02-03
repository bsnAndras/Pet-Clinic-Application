# Pet Clinic Application

This is an overview of our team project at Greenfox Academy. We were developing a web application for a pet clinic.
>**Please note that the course has finished on the October of 2024. The linked repositories mostly reflect the state of the application at the end of the course. Some minor changes have been made to the codebase though, in order to wrap up the loose ends.**

## The application
The application is a web application of a pet clinic alliance. It is intended to be used by pet owners, veterinarians and administrators.

The application consists of a frontend and a backend, each in a different repository. <br>
For the repositories containing the codebase, see the following links.

### Frontend
- Vite + React frontend application
- GitHub repository: https://github.com/bsnAndras/PET_Clinic_Frontend

### Backend
- Java SpringBoot backend application with Gradle (REST API)
- GitHub repository: https://github.com/bsnAndras/PET_Clinic_Backend


## Background
This web application was developed during a full-stack developer course, conducted by a cooperation of Greenfox Academy and CodeCool bootcamps. The application was created by 7 students at the end of the course, simulating a real-world working environment, using Scrum methodology.

## Specification
The main functionality of this single-page application is to manage users, pets and clinics.

### Main features
- The main functionalities can only be reached after registration
- After successful login, the home page is displayed depending on the role of the user
- A User then can change his data or add his pet
- An Admin should be able to register a new clinic (not implemented)

### Technical requirements
- The application is fully containerized
- The single-page application is served by a web server
- The data is stored in a database
- The database is a relational database (MySQL)
- The backend is a REST API
- The frontend is a single-page application
- The application is deployed to a cloud provider and accessible via a public URL *(we used Railway, but it is no longer available)*
- The application is tested (unit, integration, e2e)

### Non-functional requirements
- The application is responsive
- The application is accessible
- The application is secure (using JWT token for authorization)
- The application stories are tracked in a project management tool (e.g. Jira)
- The application is logging the necessary information, but not exposing PIIs
- The applications SDLC is automated where possible (CI/CD) *- in the original repository it was the case, the forked repository does not contain such mechanisms*