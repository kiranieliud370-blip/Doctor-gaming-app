# Doctor Gaming App

## Project Structure
This repository is a monorepo containing three main components:

1. **Web Game (Unity)**  
   - Located in the `web-game` directory.  
   - Built using Unity for an immersive gaming experience.  

2. **Mobile App (Flutter)**  
   - Found in the `mobile-app` directory.  
   - Developed with Flutter for cross-platform compatibility on both iOS and Android.

3. **Backend (Node.js)**  
   - The backend code resides in the `backend` directory.  
   - Created using Node.js for handling API requests and database interactions.

## Tech Stack
- **Frontend:**  
  - Unity (for web game)  
  - Flutter (for mobile app)

- **Backend:**  
  - Node.js  
  - Express.js  

- **Database:**  
  - MongoDB (or another database of choice)

- **Deployment:**  
  - Docker (for containerization)  
  - Possibly CI/CD tools (e.g., GitHub Actions, Jenkins)

## Setup Instructions
To set up the project on your local machine, follow these steps:

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/kiranieliud370-blip/doctor-gaming-app.git
   cd doctor-gaming-app
   ```

2. **Web Game Setup:**  
   - Open the `web-game` folder in Unity.
   - Ensure you have the necessary SDKs and tools installed.

3. **Mobile App Setup:**  
   - Navigate to the `mobile-app` directory and run:
   ```bash
   flutter pub get
   ```
   - Use an emulator or a physical device to test the application.

4. **Backend Setup:**  
   - From the `backend` directory, install the dependencies:
   ```bash
   npm install
   ```
   - Create a `.env` file for environment variables (see `.env.example` for structure).
   - Start the server:
   ```bash
   npm start
   ```

## Contributing
Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.