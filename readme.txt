//npm run start

client port-3000 || 5000
server port-3001

Tech Used:
Mongo DB
Express JS
React JS
Node JS
Formic and yup for form and form validation
Redux toolkit for state management
Redux persist for local storage
React router for routing
Multer for file upload
Bcrypt turns a simple password into fixed-length characters called a hash.

Steps to use:
//backend steps
1-npm i -g nodemon 
2-npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose
3-npm init -y
4-npm install mongodb

start ->npx nodemon index.js


//frontend steps
1-npx create-react-app client
2-npm i react-redux @reduxjs/toolkit redux-persist react-dropzone dotenv formik yup react-router-dom@6 @mui/material @emotion/react @emotion/styled @mui/icons-material