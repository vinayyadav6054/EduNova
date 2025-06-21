# EduNova - Full Stack Learning Platform

EduNova is a full stack learning platform built with React, Tailwind CSS, Node.js, and Express. It provides features such as user authentication, course management, payment integration, and a chatbot for enhanced user experience.

## Features

- User authentication (signup, login, OTP verification)
- Course creation, enrollment, and management
- Instructor and student dashboards
- Payment gateway integration
- Responsive UI with Tailwind CSS
- Chatbot integration for instant support

## Getting Started

Follow these steps to set up and run the project locally:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/vinayyadav6054/EduNova.git
    ```

2. **Install dependencies for both client and server:**
    ```sh
    cd EduNova
    npm install
    cd server
    npm install
    cd ..
    ```

3. **Set up environment variables:**
    - Create a `.env` file in both the root and `server` directories as needed.
    - Add required environment variables (see `.env.example` if available).

4. **Start the development servers:**
    ```sh
    npm run dev
    ```
    This will start both the client (React) and server (Node.js/Express) concurrently.

5. **Open the project in your browser:**
    - Client: [http://localhost:3000](http://localhost:3000)
    - Server API: [http://localhost:4000/api/v1](http://localhost:4000/api/v1)

## Folder Structure

- `/src` - React frontend code
- `/server` - Node.js/Express backend code
- `/src/components` - React components
- `/src/services` - API and utility functions

## Customization

- Tailwind CSS is fully configured. You can customize styles in `tailwind.config.js`.
- Update backend routes and controllers in `/server/routes` and `/server/controllers`.

## Contributing

Contributions are welcome! If you have suggestions or find issues, please open an issue or pull request.

---

**Remote Repository:**