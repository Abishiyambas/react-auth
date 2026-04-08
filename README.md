# React Auth (Frontend Only)

This project is a frontend-only authentication UI. It does not include a backend API server.

**Step-by-step setup (from opening the project in your IDE)**
1. Open a terminal in the project root (the folder that contains `package.json`).
2. Install dependencies:
   `npm install`
3. Start the dev server:
   `npm start`
4. Open the app in your browser:
   `http://localhost:3000`

**Notes**
1. The Register form sends a request to `http://localhost:3500/register`.
2. Since there is no backend in this project, you will see `ERR_CONNECTION_REFUSED` if you click Sign Up. This is expected.
3. If you want the UI to work without a backend, you can mock the API call in `src/Register.js`.
