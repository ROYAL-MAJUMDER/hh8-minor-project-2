Project Description:
The Secure Password Reset project focuses on creating a safe account recovery process using one-time tokens. It generates cryptographically secure URL tokens for password reset requests and sends them via SendGrid email service. Tokens expire within 15–30 minutes, ensuring protection against unauthorized access while maintaining a simple, reliable, and user-friendly recovery workflow.

Tools Used:
The project uses Node.js to build the backend and manage authentication processes. SendGrid is integrated for sending password reset emails securely. A database stores user data, hashed passwords, and reset tokens. Cryptographic libraries help generate secure hashes, while HTTPS ensures encrypted communication, strengthening overall system security and protecting sensitive information.

How to Run the Project:
First, install Node.js and required dependencies using npm. Configure environment variables such as database credentials and SendGrid API key. Start the server with the appropriate command (e.g., npm start). Users can request password resets through the application, receive a tokenized link via email, verify it, and securely create a new password.

I Learned:
Through this project, I learned how to design secure authentication workflows and implement one-time tokens for password recovery. I gained practical experience with Node.js, email integration, and cryptographic hashing. Additionally, I understood the importance of token expiration, data protection, and balancing security with user experience in real-world applications.
