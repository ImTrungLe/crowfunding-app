# Crowdfunding App

This is a modern crowdfunding web application built with React and Node.js. The project demonstrates a full-stack approach to building a crowdfunding platform, where users can create campaigns, support projects, and manage their accounts securely.

## Features

- User authentication and authorization
- Create, view, and manage crowdfunding campaigns
- Support campaigns with different payment methods
- Dashboard for campaign management
- Responsive and modern UI with Tailwind CSS
- RESTful API backend with Node.js and Express
- State management with Redux
- Custom hooks and reusable components

## Technologies Used

- Frontend: React, Redux, Tailwind CSS
- Backend: Node.js, Express
- Database: JSON (for demo purposes)
- Axios for API requests

## Project Structure

- `src/` — React frontend source code
- `server/` — Node.js backend server
- `public/` — Static assets

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd crowfunding-app
   ```
2. Install dependencies for both frontend and backend:
   ```bash
   npm install
   cd server && npm install
   ```
3. Start the backend server:
   ```bash
   node server.js
   ```
4. Start the frontend React app:
   ```bash
   cd ..
   npm start
   ```

The frontend will run on `http://localhost:3000` and the backend on `http://localhost:5000` by default.

## License

This project is for educational purposes only.
