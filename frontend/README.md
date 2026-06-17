# Project

Full Stack application for the **User Authentication Next.js + FastAPI + JWT** project.

## Overview

This frontend is built with Next.js and provides the user interface for authentication workflows, including:

- User registration
- User login and logout
- JWT-based authentication
- Protected routes
- Session persistence

## Tech Stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- JWT authentication

## Prerequisites

- Node.js 18 or later
- npm, yarn, or pnpm
- Running backend API

## Environment Variables

Create a `.env.local` file in the `frontend` directory:

```env
NEXT_PUBLIC_API_URL=http://localhost:8000
```

Update the value to match your backend URL.

## Installation

```bash
npm install
```

Or use:

```bash
yarn install
```

```bash
pnpm install
```

## Development

Start the development server:

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

## Production Build

Build for production:

```bash
npm run build
```

Start the production server:

```bash
npm run start
```

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run start` - Run the production server
- `npm run lint` - Run lint checks

## Features

- Authentication UI
- Secure API integration
- Protected route support
- Token-based session handling

## Project Structure

Typical structure:

```text
app/
components/
lib/
pages/
public/
styles/
```

## Notes

- Ensure the backend API is running before launching the frontend.
- Update `.env.local` if the API address changes.
- Configure CORS on the backend for browser requests.

## License

This project is part of the **User Authentication Next.js + FastAPI + JWT** repository.
