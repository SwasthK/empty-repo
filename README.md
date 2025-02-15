# TODO APP

## Clone the Repository

1. Clone the repo:
   Head over to the terminal, choose your preferred directory, and copy and paste the following command:
   - Using HTTPS: `git clone https://github.com/SwasthK/Todo-React.git`
   - Using SSH: `git clone git@github.com:SwasthK/Todo-React.git`

2. Navigate to the project directory:
   ```sh
   cd Todo-React
   ```

3. Open it in your code editor.

## Backend Setup

1. Open the terminal and navigate to the backend directory:
   ```sh
   cd backend
   ```
2. Install the dependencies:
   ```sh
   npm install
   ```
3. Rename the `.env.example` file to `.env` and add your MongoDB URI and port number. Example:
   ```env
   M_KEY=mongodb+srv://<Username>:<DbPassword>@cluster0.oqytlgg.mongodb.net/<DbNameOptional>
   PORT=3000
   ```
4. Start the backend server:
   ```sh
   npm run dev
   ```
   Access the backend at `http://localhost:3000/`.

## Frontend Setup

1. Open another terminal and navigate to the frontend directory:
   ```sh
   cd frontend
   ```
2. Install the dependencies:
   ```sh
   npm install
   ```
3. Start the frontend server:
   ```sh
   npm run dev
   ```
   Access the frontend at `http://localhost:5173/`.

## Note

This app is created for practice purposes and can run smoothly in development mode. If you plan to deploy and run this in production, make sure to update the backend API URLs in the frontend calls, which currently refer to `http://localhost:3000/api/v1/...`.

- Uses Vite + React in the frontend and Axios for data fetching, and React Icons for icons.
- Uses Express in the backend and Mongoose for database management, and Nodemon for development.

**Happy hacking!**
