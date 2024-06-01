# React Django Postgres Basic Authentication with Docker

This project implements a basic authentication system using React, Django, and PostgreSQL, all containerized with Docker. The application allows users to register, login, and logout, with JWT (JSON Web Tokens) used for authentication and HTTP-only cookies for improved security. Bootstrap is utilized for frontend styling.

The project consists of two directories: 

- `frontend`: Contains the React application
- `backend`: Contains the Django backend

## Installation

To run this project on your local machine, follow the steps below:

### Prerequisites

Ensure you have the following installed on your local machine:

- Docker

### Setup

1. Clone the repository:
    ```
    git clone https://github.com/TimamBinSaifTahmid/Basic-Auth-APP-Using-React-Django-and-Postgres-with-Docker.git
    ```
2. Change into the directory:
    ```
    cd Basic-Auth-APP-Using-React-Django-and-Postgres-with-Docker
    ```

### Build and RUN docker-compose.yml file

    ```
    sudo docker compose -f docker-compose.yml build
    ```

    ```
    sudo docker compose -f docker-compose.yml up -d
    ```

Now, your backend should run at port 8000 and client is serving through nginx on port 80. If you write http://localhost/ it will hit the base directory. 


