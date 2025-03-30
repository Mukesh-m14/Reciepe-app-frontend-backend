📌 Recipe Sharing Platform - Backend Setup

This guide will help you set up the backend for the Recipe Sharing Platform using Express.js and MongoDB Atlas.

📂 Project Structure

backend/
│-- server.js  # Main backend file
│-- .env       # Environment variables (to be created later)
│-- package.json  # Project dependencies
│-- node_modules/  # Installed packages

🚀 Step 1: Create a Backend Folder

Create a new folder and name it backend.

📝 Step 2: Create the Server File

Inside the backend folder, create a file named server.js. This file will contain the main backend code.

📦 Step 3: Initialize the Project

Open the terminal in the backend folder and run:

npm init -y

This will create a package.json file, which keeps track of project dependencies.

🔧 Step 4: Install Required Packages

Run the following command to install all the necessary packages:

npm install express mongoose cors dotenv bcryptjs jsonwebtoken nodemon

📌 What These Packages Do:

🚀 express → Helps create the backend server.

🗄️ mongoose → Connects and manages MongoDB database.

🔄 cors → Allows communication between frontend and backend.

🔑 dotenv → Manages secret environment variables (like database passwords).

🔒 bcryptjs → Hashes passwords for security.

🔐 jsonwebtoken → Handles authentication with tokens.

🔄 nodemon → Automatically restarts the server when files change.


▶️ Step 5: Start the Server

To start the backend server, run:

npm start

This will start the Express server, and your backend will be up and running! ✅


---

📌 Next Steps:

✅ Connect MongoDB Atlas to store data. ✅ Create API routes to handle user authentication and recipes. ✅ Test API endpoints using Postman or another tool.

💡 Happy Coding! 🚀
