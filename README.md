# Item Manager Backend

## Setup

1. Install dependencies:
   ```
   npm install
   ```

2. Configure environment variables:
   - Open the `.env` file
   - Replace `your_mongodb_connection_string_here` with your MongoDB Atlas connection string
   - Example: `MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/dbname`

3. Start the backend server:
   ```
   npm run dev
   ```

The server will run on `http://localhost:5000`

## API Endpoints

| Method | Endpoint         | Description       |
|--------|-----------------|-------------------|
| GET    | /api/items      | Get all items     |
| GET    | /api/items/:id  | Get item by ID    |
| POST   | /api/items      | Create new item   |
| PUT    | /api/items/:id  | Update item       |
| DELETE | /api/items/:id  | Delete item       |
