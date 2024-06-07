Task Management Application
This is a beginner-level MERN stack project demonstrating how to build a simple task management application using MongoDB, Express.js, React.js, and Node.js.

Features
User Authentication
Users can create tasks with a title and description
Users can mark tasks as completed
Task CRUD operations (Create, Read, Update, Delete)
Responsive UI
Prerequisites
Before you begin, ensure you have the following installed on your local machine:

Node.js
npm or yarn
MongoDB
Installation
1. Clone the repository:

bash
Copy code
git clone https://github.com/mohitrathore7/TASK_MANAGEMENT.git
cd TASK_MANAGEMENT
2. Install dependencies for both client and server:

bash
Copy code
cd client
npm install
cd ../server
npm install
Configuration
MongoDB Setup:
Ensure MongoDB is running on your local machine or use a MongoDB Atlas cluster.

Environment Variables:
Create a .env file in the server directory and add the following variables:

plaintext
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Running the Application
1. Start the client:

bash
Copy code
cd client
npm start
2. Start the server:

Open a new terminal window and run:

bash
Copy code
cd server
npm start
The application should now be running on http://localhost:3000 for the client and http://localhost:5000 for the server.

MongoDB Commands
Here are some useful MongoDB commands:

1. Start MongoDB:

bash
Copy code
mongod
2. MongoDB Shell:

bash
Copy code
mongo
3. Create a Database:

javascript
Copy code
use taskManagerDB
4. Show Databases:

javascript
Copy code
show dbs
5. Show Collections:

javascript
Copy code
show collections
6. Insert a Document:

javascript
Copy code
db.tasks.insertOne({ title: "Sample Task", description: "Task description", completed: false })
7. Find Documents:

javascript
Copy code
db.tasks.find()
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
