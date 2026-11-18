# Intro to Backend with MongoDB

A beginner CRUD REST API built with Node.js, Express and MongoDB (Mongoose).

## Setup
1. Clone the repo and run `npm install`
2. Create a `.env` file:
   ```
   MONGO_URI=your_mongodb_atlas_connection_string
   PORT=3000
   ```
3. Run `npm run dev`

## API Endpoints
| Method | URL | Description |
|---|---|---|
| POST | /api/products | Create a product |
| GET | /api/products | Get all products |
| GET | /api/products/:id | Get one product |
| PUT | /api/products/:id | Update a product |
| DELETE | /api/products/:id | Delete a product |

## Sample body
```json
{ "name": "Pen", "quantity": 10, "price": 5 }
```
