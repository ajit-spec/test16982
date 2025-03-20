# MEAN Stack Application

## Overview

This is a MEAN stack application, which uses MongoDB, Express.js, Angular, and Node.js to create a full-stack web application.

## Technologies

- **MongoDB**: NoSQL database used to store application data
- **Express.js**: Web application framework for Node.js
- **Angular**: Front-end web application framework
- **Node.js**: JavaScript runtime environment

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running
- Angular CLI installed (`npm install -g @angular/cli`)

### Installation

1. Clone the repository

   ```
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install server dependencies

   ```
   npm install
   ```

3. Install client dependencies

   ```
   cd client
   npm install
   cd ..
   ```

4. Create a `.env` file in the root directory with the following variables:
   ```
   MONGODB_URI=mongodb://localhost:27017/your-database-name
   PORT=3000
   JWT_SECRET=your_jwt_secret
   ```

### Running the Application

1. Start the server

   ```
   npm start
   ```

2. Start the Angular client (in a separate terminal)

   ```
   cd client
   ng serve
   ```

3. Open your browser and navigate to `http://localhost:4200`

## Project Structure

- `/client` - Angular front-end application
- `/server` - Express.js back-end application
- `/models` - MongoDB data models
- `/routes` - API routes
- `/controllers` - Request handlers
- `/middleware` - Custom middleware functions

## API Endpoints

- `GET /api/resource` - Get all resources
- `POST /api/resource` - Create a new resource
- `GET /api/resource/:id` - Get a specific resource
- `PUT /api/resource/:id` - Update a specific resource
- `DELETE /api/resource/:id` - Delete a specific resource

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
