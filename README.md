# Activity Manager

Activity Manager is a Task Tracker web application that allows users to securely sign up, log in, and manage their tasks. Built using React.js for the frontend and C++ for the backend, this application combines modern web technologies with powerful backend programming to provide a seamless task management experience.

## Features

- **User Authentication**: Secure sign-up and login functionalities.
- **Task Management**: Users can add, edit, and delete tasks within a user-friendly interface.
- **Automated Testing and Deployment**: Utilizes GitHub Actions for continuous integration and deployment.
- **GitHub Integration**: Uses GitHub for project management, including the use of issues for tracking and branches for organized feature development.

## Technologies Used

- **React.js**: For building the interactive user interface.
- **C++**: Used for server-side logic.
- **GitHub Actions**: For automating tests and deployment.
- **GitHub Pages**: Hosting for the frontend.
- **Heroku**: Hosting for the backend services.

## Getting Started

To get started with Activity Manager, follow these instructions:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourgithub/activity-manager.git
   ```
2. **Install Dependencies**:
   Navigate to the project directory and install the necessary dependencies.
   ```bash
   # For the frontend
   cd frontend
   npm install
   
   # For the backend
   cd ../backend
   make setup
   ```
3. **Environment Setup**:
   Set up the necessary environment variables in your `.env` files within the frontend and backend directories.
4. **Run the Application**:
   ```bash
   # Start the frontend
   npm start
   
   # Start the backend
   ./run_server.sh
   ```

## Documentation

For more detailed information, visit the `docs/` directory which includes complete setup, configuration, and usage instructions.

## Contributing

We welcome contributions from the community, whether it's fixing bugs, improving the documentation, or adding new features. Please use the standard fork-and-pull request workflow.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

Your Name - your.email@example.com  
Project Link: [Activity
