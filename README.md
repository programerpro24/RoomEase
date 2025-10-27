# Run On Local System : 
http://localhost:8080/listings


# RoomEase - Full-Stack Room Rental Platform

This is a full-stack web application built with Node.js, Express, MongoDB, and EJS. The platform allows users to browse, add, edit, and delete property listings, incorporating a complete user authentication and authorization system.

This project focuses on Server-Side Rendering, using EJS as the templating engine to dynamically generate HTML on the server.

# Features

# Authentication & Authorization:

Secure user registration, login, and logout functionality implemented using Passport.js (passport-local, passport-local-mongoose).

Persistent user sessions are managed using express-session and stored in MongoDB via connect-mongo.

# Full CRUD Operations: 
Authenticated users can perform all CRUD (Create, Read, Update, Delete) operations for their own property listings.

# Cloud Image Uploads:

Seamless image uploading for listings directly to the cloud.

Uses Multer for handling multipart/form-data and Cloudinary (multer-storage-cloudinary) for cloud storage, keeping the server stateless.

# Server-Side Schema Validation:

Employs Joi to validate incoming data (like form submissions) on the server, ensuring data integrity before it reaches the database.

# Flash Notifications: 
Uses connect-flash to provide users with feedback on their actions (e.g., 'Successfully logged in', 'Listing deleted').

# RESTful Routing: 
Follows a clean and semantic RESTful routing structure for all application endpoints.

# Tech Stack

# Backend:

Node.js

Express.js

Express Session

Passport.js (Local Strategy)

Multer (File Upload Handling)

Cloudinary (Cloud Image Storage)

Joi (Schema Validation)

Method-Override

# Frontend (Templating Engine):

EJS (Embedded JavaScript)

EJS-Mate (For layouts and partials)

# Database:

MongoDB

Mongoose (ODM - Object Data Modeling)

Connect-Mongo (For session storage)
