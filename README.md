# Shiprocket Integration API (Production Ready)

A backend API built for seamless integration between an e-commerce platform and Shiprocket logistics service.

Features
- Order creation and automatic courier assignment
- Real-time tracking and label generation
- Status sync and webhook-ready endpoints
- Deployed on AWS EC2 and MongoDB Atlas (M10)

Tech Stack
- Node.js / Express.js
- MongoDB Atlas
- JWT Auth
- AWS EC2 (Ubuntu)
- cURL / Axios for Shiprocket API

Setup Instructions

1. Clone the repository
2. Run `npm install`
3. Create a `.env` file based on `.env.example`
4. Run `npm start` or `nodemon` to start dev server

Security
- Sensitive data stored in environment variables
- Do not expose keys or tokens publicly


