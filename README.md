# Login Handler

Login Handler is a React project designed to handle user authentication. It simplifies the login process after signing up, offering a seamless user experience. The main feature of this application is that once a user logs in, they won't be prompted to log in again until they manually log out. This is achieved using the `useEffect` and `useState` hooks, along with the concept of React fragments and `useRef` for rendering via ReactDOM. For styling, CSS Modules are employed.

## Features

- **User Authentication**: Easily sign up and log in with minimal hassle.
- **Persistent Login**: After logging in, the user will remain authenticated until they choose to log out.
- **React Components**: The project uses React components to maintain a structured and modular codebase.
- **CSS Modules**: Styling is done using CSS Modules, ensuring that styles are scoped to their respective components.
- **Efficient Rendering**: React's `useRef` and `useEffect` hooks are utilized to optimize rendering and maintain a smooth user experience.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your development environment.
- A basic understanding of React and its core concepts.

## Getting Started

Follow these steps to get the project up and running on your local machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/sananawaz642/Login-Handler.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Login-Handler
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and go to [http://localhost:3000](http://localhost:3000) to see the application in action.

## Usage

1. **Sign Up**: Create a new account by providing your details.
2. **Log In**: Log in with your credentials.
3. **Access the App**: Once logged in, you can access the main application without being prompted to log in again.
4. **Log Out**: To log out and end the session, click the "Log Out" button.

## Folder Structure

The project follows a structured folder hierarchy:

- `src/`
  - `components/`: Contains React components.
  - `css/`: Houses CSS Modules for styling.
  - `App.js`: Main application component.
  - `index.js`: Entry point for the React application.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Commit your changes with a clear and concise commit message.
5. Push your changes to your fork.
6. Create a pull request to the main repository's `main` branch.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
