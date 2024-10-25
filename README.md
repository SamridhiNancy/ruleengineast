# ruleengineast
Here’s the README in plain text format:

RuleEngineAST

This project is a rule engine system for determining user eligibility based on attributes like age, department, income, and spending. It consists of two parts: the frontend and **backend. The frontend is built using React, and the backend uses Node.js, Express, and MongoDB.

---

Instructions to Run the Project

1. Frontend Setup

Steps to run the frontend:

1. Open Terminal:  
   Navigate to the `frontend` directory:  
   `cd frontend`

2. Install Dependencies:  
   Install all necessary dependencies:  
   `npm install`

3. Start the Application:  
   Start the frontend with the following command:  
   `npm start`

4. Access the Application:  
   Once the application starts, it will be available on your browser at:  
   `http://localhost:3000`

---

2. Backend (zeotapbackend1) Setup

Steps to run the backend:

1. Open Terminal:  
   Navigate to the `zeotapbackend1` directory:  
   `cd zeotapbackend1`

2. Install Dependencies:  
   Install all necessary backend dependencies:  
   `npm install`

3. Set Up Environment Variables:  
   Create a `.env` file in the `zeotapbackend1` directory and add the following variables:
   - `MONGOURI=your-mongo-db-url-here`
   - `PORT=4000`

   Replace `your-mongo-db-url-here` with your MongoDB URI.

4. Start the Backend Server:  
   Run the backend using:  
   `npm start`

5. Access the Backend:  
   The backend will be running at:  
   `http://localhost:4000`


3. Environment Variables

For the backend to function properly, the `.env` file must contain the following:

MONGOURI: The MongoDB connection string.
PORT: The port number for the backend, which you can set to `4000` or any other available port.

Example `.env` file:


MONGOURI=mongodb+srv://username:password@cluster0.mongodb.net/dbname?retryWrites=true&w=majority
PORT=4000


4. Technologies Used

Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Environment Management: dotenv

