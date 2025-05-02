# Simple CRUD API

A basic RESTful API built using **Node.js**, **Express**, and **MongoDB**. This API allows users to perform CRUD operations on product data.

## 🌐 Live URL

[https://simple-crud-api-lhl4.onrender.com](https://simple-crud-api-lhl4.onrender.com)

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB** (via Mongoose)
- **dotenv** for environment variables
- **cors** for cross-origin requests
- **Hosted on Render**

---

## 📦 API Endpoints

| Method | Endpoint                | Description                     |
|--------|-------------------------|---------------------------------|
| GET    | `/api/products`         | Get all products                |
| GET    | `/api/products/:id`     | Get a single product by ID      |
| POST   | `/api/products`         | Create a new product            |
| PUT    | `/api/products/:id`     | Update a product by ID          |
| DELETE | `/api/products/:id`     | Delete a product by ID          |

---

## 🚀 Setup Instructions

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```
3. Create a `.env` file in the root with the following content:

   ```env
   PORT=6969
   MONGODB_URI=your_mongodb_connection_string
   ```
4. Run the development server:

   ```bash
   npm run dev
   ```

---

## 📁 Project Structure

```
/controllers     -> Request handlers
/models          -> Mongoose schema
/routes          -> API routes
/config          -> MongoDB connection
server.js        -> Main entry file
```

---

## 🧪 Sample Product

```json
{
  "name": "Test Product",
  "price": 99.99,
  "description": "A test product entry."
}
```
