# Welcome to flight Services

## Project Setup
- clone the project on your local
-Execute `npm i` on your terminal of the downloaded project
-Create a `.env` file in root directory and add the following environment variable
    - `PORT = 3000`
- Inside the `src/config` folder create a new file `config.jason` and then add the following piece of json

```
{
  "development": {
    "username": <YOUR_DB_LOGIN_NAME>,
    "password": <YOUR_DB_PASSWORD>,
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

```

-Once you have added your db config as listed above, go to the src folder from your terminal and execute `npx sequelize db:create`.