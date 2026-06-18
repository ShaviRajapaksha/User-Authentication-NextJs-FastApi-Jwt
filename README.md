# User Authentication with Next.js, FastAPI, and JWT

A full-stack authentication starter project using Next.js on the frontend and FastAPI on the backend with JWT-based authentication.

## Features

- User registration
- User login
- JWT token authentication
- Protected routes and endpoints
- Full-stack separation of frontend and backend

## Tech Stack

- Next.js
- FastAPI
- Python
- React
- JWT

## Project Structure

- `frontend/` - Next.js client application
- `backend/` - FastAPI API server

## Getting Started

### Prerequisites

- Node.js
- Python 3.10+
- npm or yarn

### Backend Setup
create venv first
```powershell

.venv\Scripts\Activate.ps1
pip install -r requirements.txt
uvicorn src.api.main:app --reload
```

### Frontend Setup

```powershell
cd frontend
npm install
npm run dev
```

## Environment Variables

Create a `.env` file for required configuration, such as:

- `JWT_SECRET`
- `API_URL`

## Usage

1. Start the backend server.
2. Start the frontend application.
3. Register a new user.
4. Log in to receive a JWT token.
5. Access protected routes.

## License

This project is provided as-is.
