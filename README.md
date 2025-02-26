# Task Management Application

## Overview
This is a **Task Management Application** built with **React (TypeScript)** for the frontend and **Node.js (Express & TypeScript)** for the backend. It allows users to create, update, delete, and manage tasks efficiently while incorporating advanced async operations and automatic task timeout handling.

## Deployment
### Frontend
Deployed on **Vercel**: [Live Link](https://seequenze-technologies-assignment-eta.vercel.app/)

### Backend
Deployed on **Vercel**: [Live API](https://seequenze-technologies-assignment-api.vercel.app/)

## Features
### Frontend
- Built using **React with TypeScript**.
- **Task Management**: Create, update, delete, and categorize tasks.
- **Category Slider**: Navigate between "To Do", "In Progress", "Done", and "Timeout".
- **Async API Calls**: Fetch tasks with error handling and loading states.
- **Timeout Handling**: Tasks automatically move to "Timeout" after exceeding their duration.
- **Styled UI**: Well-structured UI with loading indicators and user-friendly interactions.

### Backend
- Built with **Node.js, Express, and TypeScript**.
- **CRUD API Endpoints** for managing tasks.
- **Streaming Data API**: Fetches and integrates additional live stream data.
- **Automatic Timeout**: Backend logic to check and update task status based on duration.
- **Proper Error Handling & Validation**.

## Project Structure
```
SEEQUENZE-TECHNOLOGIES
├── node_modules/
├── public/
├── Server/
├── src/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.html
│
├── .gitignore
├── eslint.config.js
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.json
├── vite.config.ts
├── vercel.json
```

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v16+ recommended)
- **npm** or **yarn**

### Clone the Repository
```sh
git clone https://github.com/yourusername/task-management-app.git
cd task-management-app
```

### Install Dependencies
```sh
npm install  # For both frontend and backend
```

## Running the Application

### Backend
```sh
npx nodemon src/index.ts
```
The backend will start running on `http://localhost:5000`

### Frontend
```sh
npm run dev
```
The frontend will be accessible at `http://localhost:5173`

## API Endpoints
| Method | Endpoint        | Description          |
|--------|---------------|----------------------|
| GET    | /tasks        | Fetch all tasks      |
| GET    | /tasks/:id    | Fetch a task by ID   |
| POST   | /tasks        | Create a new task    |
| PUT    | /tasks/:id    | Update a task        |
| DELETE | /tasks/:id    | Delete a task        |
| GET    | /streaming    | Fetch streaming data |

## Technologies Used
### Frontend:
- React with TypeScript
- React Hooks (useState, useEffect, useContext)
- Vite for development
- CSS Modules / Styled Components
- Axios for API requests

### Backend:
- Node.js with Express.js
- TypeScript
- MongoDB
- Nodemon for development
- Async/Await for API handling

## Contribution
Feel free to contribute by following these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Open a Pull Request.

## Author
**Your Name**  
GitHub: [Gaurav-Soni24](https://github.com/gaurav-soni24)  
Email: sonigaurav2021@gmail.com

## License
This project is licensed under the MIT License.