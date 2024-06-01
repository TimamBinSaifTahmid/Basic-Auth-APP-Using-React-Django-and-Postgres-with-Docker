# React Django Postgres Basic Authentication with Docker

This project implements a basic authentication system using React, Django, and PostgreSQL, all containerized with Docker. The application allows users to register, login, and logout, with JWT (JSON Web Tokens) used for authentication and HTTP-only cookies for improved security. Bootstrap is utilized for frontend styling.

The project consists of two directories: 

- `frontend`: Contains the React application
- ``: Contains the Django backend

## Installation

To run this project on your local machine, follow the steps below:

### Prerequisites

Ensure you have the following installed on your local machine:

- Docker

### Setup

1. Clone the repository:
    ```
    git clone https://github.com/<yourusername>/<yourrepository>.git
    ```
2. Change into the directory:
    ```
    cd <yourrepository>
    ```

### Server

1. Navigate to the `server` directory:
    ```
    cd server
    ```
2. Install Django and other dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Create a virtual environment (Optional but recommended):
    ```
    python -m venv env
    ```
4. Activate the virtual environment:
    On Windows:
    ```
    .\env\Scripts\activate
    ```
    On MacOS/Linux:
    ```
    source env/bin/activate
    ```
5. Create a `.env` file in the `server` directory and add your secret key like this: 
    ```
    SECRET_KEY=<your-secret-key>
    ```

### Client

1. Navigate to the `client` directory:
    ```
    cd ../client
    ```
2. Install all the dependencies:
    ```
    npm install
    ```
3. Run the client:
    ```
    npm start
    ```

Now, your application should be running at `localhost:3000`.

Note:
- The Django server should be running at the same time as the React application for the system to function properly.
- The application uses the email field instead of the username field for user identification.
