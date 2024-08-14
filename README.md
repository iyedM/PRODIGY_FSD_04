for the frontend:
1. Clone the repository.
2. Run yarn install to install dependencies.
3. Create a .env.development file in the root directory and paste the following:

VITE_API_URL=

VITE_WEBSOCKET_URL=

4. Run yarn start or npm run start depending on which package manager you use to start the project in development mode.

for the backend:
1. Clone the repository.
2. Run yarn install to install dependencies.
3. Create a .env.development file in the root directory and paste the following:
PORT=
COOKIE_SECRET=
ENVIRONMENT=

MYSQL_HOST=
MYSQL_PORT=
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_BD=
you can use railway for hosted mysql database
4. Run yarn start:dev or npm run start:dev depending on which package manager you use to start the project in development mode.
