# MERN Stack

**MongoDB**: A document-based open source database  
**Express**: A web application framework for Node.js  
**React**: A JavaScript front-end library for building user interfaces  
**Node.js**: JavaScript run-time environment that executes JavaScript code outside of a browser (such as a server)  
and **mongoose**: simple, schema-based solution to model application data

# PROJECT OVERVIEW

Purpose: Assign an exercise to a user  
Features:

1. New user can be created
2. New exercise can be created and assigned to a specific user
3. Old exercise can be updated
4. All the data is stored using MongoDD

# MongoDB:

Terms

1. Database
2. Collection
3. Document
4. Index
5. $lookup
6. Reference

> MongoDB uses JSON-like documents with optional schemas

# STEPS:

1. Create the BACKEND and connect to MongoDB
   > inside the backend folder: <code>npm install express cors mongoose dotenv</code>
   > Install nodemon globally to use it in command line: <code>npm install -g nodemon</code>
2. Then Create React front end and connect to the backend
3. Remember to run both the backend and frontend in order to allow the project to work successfully

# SETUP

1. Register MongoDB Atlas for mongoDB access
2. Run <code>npm install</code> in the project folder and also in the **backend** folder
3. Go to **backend** folder, create **.env** file and create **ATLAS_URI** variable with the string you have from MongoDB Atlas to successfully connect to the database. Make sure to replace **\<password>** and **\<dbname>**
4. Run <code>npm start</code> in the current **project** folder
5. Locate into the **backedn** folder and run <code>nodemon server</code>
