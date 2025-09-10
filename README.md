Real Estate Management Application

A full-stack real estate platform developed using TypeScript, React, Node.js, and MongoDB, designed to streamline property listing, search, and management processes.

🚀 Features

Property Listings: View and filter properties by location, price, and type.

User Authentication: Secure login and registration using JWT.

Admin Dashboard: Manage property listings, users, and transactions.

Responsive Design: Optimized for both desktop and mobile devices.

🛠️ Tech Stack

Frontend: React, TypeScript, CSS

Backend: Node.js, Express

Database: MongoDB

Authentication: JWT

📦 Installation
1. Clone the repository
git clone https://github.com/mayanksdadhich6/real-estate-management.git
cd real-estate-management

2. Install dependencies
Client
cd client
npm install

Server
cd server
npm install

3. Configure environment variables

Create a .env file in both the client and server directories and add the following variables:

# Client
REACT_APP_API_URL=http://localhost:5000

# Server
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

4. Run the application
Client
cd client
npm start

Server
cd server
npm start


The application will be running at http://localhost:3000
.
