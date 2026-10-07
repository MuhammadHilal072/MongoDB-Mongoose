# MongoDB & Mongoose Notes

Practice projects from my journey learning MongoDB with Mongoose and Express.

## Topics covered

| `MONGO` | Mongoose basics: connecting to MongoDB, schemas, models, CRUD (`books.js`) | `index.js` |
| `MongoExpress` | A full Express + Mongoose app with views, static files, custom error handling, and seed data (`init.js`) | `index.js` |
| `RELATIONSHIPS IN MONGODB` | Modeling relationships between collections in Mongoose | models only |

## Tech

Node.js, Express, MongoDB, Mongoose, EJS

## Requirements

MongoDB installed and running locally (`mongodb://127.0.0.1:27017`).

## How to run

Each folder is a separate project with its own dependencies. For example:

    cd MongoExpress
    npm install
    node init.js
    node index.js

Then open http://localhost:8080.

`node init.js` adds sample data to the `fakewhatsapp` database, so run it once before starting the app.

For `MONGO`, run `npm install` and then `node index.js`.

## Author

Muhammad Hilal