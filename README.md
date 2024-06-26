## How to run with Docker?
1. On the root folder run:
docker-compose build && docker-compose up -d

2. The client (React) will be running on localhost:3001, the server (Node) will be running on localhost:3000


## What would I improve in this code?
1. Security on both applications: Securing the endpoints with JWTs or similar and adding a Login screen and maybe roles to the Frontend.
2. Add a relational database to the Backend to relate Accounts with Transfers and store the information securely.
3. Add a better design to the Front end.
4. Add configurations for multiple environments and create a .env file for local development.
5. Add tests. I like to follow Test Driven Development, it saves a lot of headaches later.
6. Add validations on both sides of the application.
7. Secure the backend endpoints.
2. Restrict elements of the frontend depending on the user roles.
