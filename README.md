# To-do app

This is my old todo app, written with JavaScript and featuring MongoDB, Express.js, Bootstrap, and EJS

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file. You can also copy it from .env_example.

`MONGO_URI` - Your mongodb connection string

`DATABASE_NAME = 'TODO'` - Database name

`SESSION_SECRET` - Secret used to sign the session cookie

`PORT` - Server port

## Run Locally

Clone the project

```bash
  git clone https://github.com/JustEnough1/To-do-app.git
```

Install dependencies

```bash
  npm i
```

Add environment variables

```bash
  Rename .env-example to .env and set values
```

Start the server

```bash
  npm start
```
