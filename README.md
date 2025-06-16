# Task & Employee Manager

A modern task and employee management system built with React, Node.js, and MongoDB. The system provides an intuitive user interface for managing employees and tasks within an organization.

## Key Features

- ✨ Modern and intuitive user interface
- 👥 Employee Management (Add, Edit, Delete)
- ✅ Task Management (Add, Edit, Delete)
- 🔐 Secure Authentication System
- 📱 Responsive Design for all devices
- 🎨 Material-UI based interface

## Technologies Used

### Frontend
- React.js
- Material-UI
- React Router
- Axios
- Date-fns

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

## System Requirements

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/task-employee-manager.git
cd task-employee-manager
```

2. Install server dependencies:
```bash
npm install
```

3. Install client dependencies:
```bash
cd client
npm install
```

4. Create `.env` file in the root directory:
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/task-manager
JWT_SECRET=your-secret-key-here
```

5. Initialize the database:
```bash
npm run init-db
```

## Running the Application

1. Start the server:
```bash
npm run dev
```

2. In a new terminal, start the client:
```bash
cd client
npm start
```

3. Open your browser at: `http://localhost:3000`

## Default Login Credentials

- Username: admin
- Password: admin123

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Your Name - [@your-twitter](https://twitter.com/your-twitter)
- Email - your.email@example.com
- Project Link: [https://github.com/your-username/task-employee-manager](https://github.com/your-username/task-employee-manager) 