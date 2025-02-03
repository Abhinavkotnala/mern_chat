# MERN Chat Application

## Overview
A full-stack real-time chat application built using the MERN (MongoDB, Express, React, Node.js) stack with modern web technologies.

## Features
- User authentication
- Real-time messaging
- Personal user avatars
- Responsive design
- Tailwind CSS styling

## Prerequisites
- Node.js (v14 or later)
- MongoDB
- Yarn or npm

## Installation

### Clone the Repository
```bash
git clone <your-repo-url>
cd mern-chat-master
```

### Backend Setup
```bash
cd api
yarn install
# or
npm install
```

### Frontend Setup
```bash
cd client
yarn install
# or
npm install
```

### Environment Variables
Create `.env` files in both `api` and `client` directories with necessary configurations:

#### API `.env`
- `MONGODB_URL`: Your MongoDB connection string
- `JWT_SECRET`: Secret key for authentication
- `PORT`: Backend server port (default: 4040)

#### Client `.env`
- `VITE_API_URL`: Backend API base URL

## Running the Application

### Start Backend
```bash
cd api
yarn start
# or
npm start
```

### Start Frontend
```bash
cd client
yarn dev
# or
npm run dev
```

## Technologies Used
- MongoDB: Database
- Express.js: Backend framework
- React: Frontend library
- Node.js: Runtime environment
- Tailwind CSS: Styling
- Vite: Frontend build tool
- Socket.io: Real-time communication

## Project Structure
- `api/`: Backend Node.js/Express server
  - `models/`: Mongoose data models
  - `routes/`: API endpoint definitions
- `client/`: React frontend
  - `src/`: Component and application logic
  - `components/`: Reusable React components

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.
