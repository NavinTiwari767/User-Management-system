🚀 User Management System API
A simple user management API with authentication and authorization using Node.js, Express.js, MongoDB, and JWT.

📌 Features
✅ User Registration
✅ User Login
✅ Get User Profile (Authenticated users only)
✅ Update User Profile (Authenticated users only)
✅ Delete User (Authenticated users only)
✅ JWT-based Authentication
✅ Error Handling & Validation
✅ API Documentation (Swagger)
✅ Unit Tests

🏗️ Tech Stack
Backend: Node.js, Express.js

Database: MongoDB (Mongoose)

Authentication: JWT (JSON Web Token)

Validation: Express Validator

Documentation: Swagger (OpenAPI)

Testing: Jest / Mocha & Chai
🔧 Installation & Setup

git clone <your-repo-url>
cd user-management-api
npm install
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
npm start
npm run dev


🛠️ API Endpoints
📝 Authentication
Register a new user
Method: POST
Endpoint: /api/auth/register

Authenticate user & get token
Method: POST
Endpoint: /api/auth/login

👤 User Management (Protected)
Get user profile (Requires Token)
Method: GET
Endpoint: /api/users/profile

Update user profile (Requires Token)
Method: PUT
Endpoint: /api/users/profile

Delete user (Requires Token)
Method: DELETE
Endpoint: /api/users/profile

