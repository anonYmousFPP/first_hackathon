## HACKATHON

This is my first hackathon, in which we create a UPI prototype with MERN Stack technology.

 - Signup page for new user registration: (http://localhost:5173/signup)
 - Signin: This is the second page of my site where an already registered user can log in again: (http://localhost:5173/signin)
 - Dashboard: Users can send any amount of money to any user who must be present in our MongoDB database. URL for dashboard(http://localhost:5173/dashboard)


Steps for running frontend tech: 
1. Go inside the frontend folder via cd ./frontend.js/
2. Install npm package modules for the React libraries: npm i
3. Type npm run dev in the compiler.


Steps for running backend tech:
1. Go inside the backend folder.
2. Install npm package modules for Node.js libraries: npm i
3. Type node index.js command in the compiler.

now download all libraries separately for each libraries "npm i zod, middleware, jsonwebtoken, express, mongoose, cors"

Now the final step is to connect the MongoDB with Mongoose by pasting the MongoDB Compass link (like: mongodb+srv://username:password@cluster0.a4lhea8.mongodb.net/) inside the db.js file.