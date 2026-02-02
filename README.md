# Money Manager – Backend

This backend service powers the Money Manager application by handling income, expenses, account transfers, filtering, and financial summaries. It ensures structured data storage and reliable API responses.

The backend is designed to support real-world finance tracking with clear business rules.

---

## Features

- Manage income transactions
- Manage expense transactions
- Category-based tracking:
  - Food, Fuel, Movie, Loan, Medical, etc.
- Division-based classification:
  - Personal
  - Office
- Date and time tracking for all transactions
- Filters:
  - Category
  - Division
  - Date range (between two dates)
- Editing restriction:
  - Transactions can be edited only within 12 hours
- Financial summaries:
  - Weekly income and expenditure
  - Monthly income and expenditure
  - Yearly income and expenditure
  - Category-wise expense summary
- Account-to-account transfer tracking
- Complete transaction history support
- RESTful API architecture

---

## Tech Stack

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose

---

## Project Structure

src/
controllers/    Business logic  
models/         MongoDB schemas  
routes/         API routes  
middleware/     Validation and restrictions  
config/         Database configuration  
server.js  

---

## Installation and Setup

1. Clone the repository  
   git clone https://github.com/VIJAY-PRASATH-R/money-manager-backend.git

2. Navigate to the project directory  
   cd money-manager-backend

3. Install dependencies  
   npm install

4. Create a .env file and add the following:
   MONGO_URI=your_mongodb_atlas_connection_string  
   PORT=5000

5. Start the server  
   npm start

---

## API Integration

- The backend is deployed and connected with the frontend application.
- Any income or expense added is reflected across all summaries and history views.

---

## Business Rules Implemented

- Transactions are editable only within 12 hours of creation
- Consistent data aggregation for dashboard views
- Structured and scalable database design

---

## Notes

- Clean and modular backend architecture
- Designed for scalability and maintainability
- Follows standard backend development practices

---

## Author

Vijay Prasath R  
Fullstack Developer
