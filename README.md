# Sudario's Inventory Management System

## Installing

### Database setup

1. Go to src/db/mysql.js
2. Add connection details for your mysql database. It should look like this
   ```javascript
   import mysql from "mysql2/promise"
   export const connection = await mysql.createConnection({
     host: "localhost",
     user: "USERNAME",
     password: "PASSWORD",
     database: "DATABASE_NAME",
   })
   ```
3. Copy everything from src/db/schema.sql and run it in your database to initialize the schema. You can run this again if you want to reset the database

### Running the server

1. Go to your downloaded folder
2. Run the server in your terminal
   ```bash
   npm run dev
   ```
3. Visit http://localhost:3000
# sudario-inventory-management-system
