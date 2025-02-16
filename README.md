# Full Stack Demo Application

This is a full stack demo application using the MERN stack (MongoDB, Express, React, Node.js) with TypeScript for both frontend and backend.

## Project Structure

full-stack-demo/
├── my-frontend/ # React frontend
├── my-backend/ # Node.js backend
├── .gitignore
├── README.md
└── package.json

## Getting Started

### Prerequisites

- Node.js and npm installed
- Git installed

### Frontend Setup

1. **Create the frontend directory**:

   mkdir my-frontend

2. **Navigate to the frontend directory**:

   cd ./my-frontend

3. **Initialize a new Vite project**:

   npm create vite@latest .

4. **Choose React and then TypeScript when prompted**.

5. **Install dependencies**:

   npm install axios react-router-dom yup @hookform/resolvers react-hook-form react-hot-toast @mui/icons-material @mui/styles @mui/material

6. **Run the development server**:

   npm run dev

### Backend Setup

1. **Create the backend directory**:

   mkdir my-backend

2. **Navigate to the backend directory**:

   cd ./my-backend

3. **Initialize a new Node.js project**:

   npm init -y

4. **Install dependencies**:

   npm install express dotenv cors mongoose

5. **Install TypeScript and type definitions**:

   npm install --save-dev typescript @types/express @types/cors ts-node nodemon

6. **Initialize TypeScript configuration**:

   npx tsc --init

### Running the Application

1. **Start the backend server**:

   cd my-backend
   npx ts-node src/index.ts

2. **Start the frontend development server**:

   cd my-frontend
   npm run dev

### Pushing to GitHub

1. **Navigate to the root directory of your project**:

   cd path/to/full-stack-demo

2. **Initialize a Git repository** (if not already initialized):

   git init

3. **Create a `.gitignore` file**:

   # Node.js

   my-backend/node_modules/
   my-backend/.env

   # React

   my-frontend/node_modules/
   my-frontend/build/

4. **Add and commit your files**:

   git add .
   git commit -m "Initial commit of full stack demo application"

5. **Add the remote repository URL**:

   git remote add origin https://github.com/Yuvrajdhakrey8/full-stack-demo.git

6. **Push your changes to the remote repository**:
   git push -u origin main

### Additional Tips

- **Branching**: Consider creating branches using `git checkout -b branch-name` for different features or fixes.
- **Pull Requests**: Use pull requests to merge changes from different branches.
- **CI/CD**: Set up Continuous Integration/Continuous Deployment (CI/CD) pipelines to automate testing and deployment processes.

By following these steps, you will successfully set up and push your frontend and backend code to your GitHub repository without conflicts.
