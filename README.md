# Code Notes

Code Notes is a simple web application for creating, viewing, and managing code snippets and notes. It consists of a React frontend and an Express backend, designed for easy local development and deployment.

## Features

- Create, view, and delete notes with code or plain text
- Syntax highlighting for multiple programming languages
- Responsive and clean UI with Tailwind CSS
- Persistent storage of notes on the backend

## Project Structure
codenotes-backend/ # Express backend API
codenotes-frontend/ # React frontend (Vite + Tailwind CSS)


## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Setup

```sh
git clone --recurse-submodules https://github.com/deadloop-dev/codenotes.git
cd codenotes

# Install dependencies
cd codenotes-backend
npm install
cd ..
cd codenotes-frontend
npm install
cd ..

# start the backend
# The backend will run on http://localhost:3000 by default.
cd codenotes-backend
npm start

# start the frontend
# The frontend will run on http://localhost:5000 by default.

cd codenotes-frontend
npm run dev
```

### Configuration
The frontend expects the backend API URL in .env as VITE_API_URL (default: http://localhost:3000/api).
The backend stores notes in a local JSON file (data/data.json by default).

### Scripts
#### Frontend
```sh
npm run dev # — Start development server
npm run build # — Build for production
npm run preview # — Preview production build
```
#### Backend
```sh
npm start # — Start the backend server
npm test # — Run backend tests
```
## License
MIT

Made with ❤️ for code snippets and notes.
_A simple test web application for security testing purposes._
