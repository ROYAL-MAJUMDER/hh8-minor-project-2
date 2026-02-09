Project Description 

This project implements a secure password reset system using Node.js and MongoDB. It allows users to recover accounts through time-limited reset tokens. The system ensures security by validating users, generating cryptographic tokens, expiring them automatically, and securely hashing new passwords before storing them in the database.


 Tools Used 

The project uses Node.js with Express for backend development, MongoDB for database storage, and Mongoose for object modeling. Bcrypt is used for password hashing, Crypto for secure token generation, Dotenv for environment variables, Nodemailer for email delivery, and Kali Linux as the development environment.


 How to Run the Project 

Start MongoDB service and verify database connection. Navigate to the project directory and install dependencies using npm install. Configure environment variables in the .env file. Run the server using node server.js. Use curl or Postman to test forgot-password and reset-password API endpoints.


 What I Learned 

I learned how to design a secure password recovery flow, implement token-based authentication, and handle sensitive user data securely. I gained practical experience with Node.js, MongoDB, API testing using curl, debugging backend errors, and understanding real-world security practices in authentication systems.
