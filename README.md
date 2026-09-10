# Hon Hon

**Hon Hon** is a cross-platform focus and reading-time management application built with **React Native**, **Expo**, **Node.js**, and **MongoDB**.

The project combines a mobile frontend with a dedicated backend so users can manage focus sessions and persist their activity across sessions.

## Overview

Hon Hon was created to help users stay focused while reading by providing a structured mobile experience around time management and session tracking.

The repository contains both the application source code and academic project documentation from the Hybrid Application Development (ITE-434) course.

## Key features

- Mobile-focused reading and focus workflow
- Time-management / focus-session experience
- React Native application built with Expo
- Dedicated Node.js backend
- MongoDB-backed persistence
- Clear separation between frontend and backend projects
- Project documentation and presentation assets kept alongside the source

## Tech stack

| Area | Technology |
| --- | --- |
| Mobile frontend | React Native, Expo |
| Language | TypeScript / JavaScript |
| Backend | Node.js, Express |
| Database | MongoDB |
| Package management | npm |
| Development runtime | Nodemon |

## Repository structure

```text
honhon-app/
├── Documents/             # Academic project documents and deliverables
│   ├── Phase 1/
│   ├── Phase 2/
│   └── Phase 3/
└── Hon-Hon-app/
    ├── frontend/          # React Native / Expo application
    └── backend/           # Node.js / Express API
```

## Getting started

### Prerequisites

Install the following before running the project:

- Git
- Node.js and npm
- Expo-compatible development environment
- Access to a MongoDB database

### Clone the repository

```bash
git clone https://github.com/NiraphatK/honhon-app.git
cd honhon-app
```

## Frontend setup

Navigate to the mobile application:

```bash
cd Hon-Hon-app/frontend
```

Install dependencies:

```bash
npm install
```

Start Expo:

```bash
npx expo start
```

Use the Expo development tools to open the application on a compatible Android/iOS simulator or physical device.

## Backend setup

Open another terminal and navigate to the backend:

```bash
cd Hon-Hon-app/backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file with the required MongoDB connection and server configuration:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

Start the development server:

```bash
npm run dev
```

## Architecture

At a high level, Hon Hon follows a simple client/server structure:

```text
React Native / Expo client
          |
          | HTTP API
          v
Node.js / Express backend
          |
          v
       MongoDB
```

Keeping the frontend and backend separated makes the project useful as a practical example of connecting a mobile application to an external API and persistent database.

## Academic background

Hon Hon was developed as a final project for **Hybrid Application Development (ITE-434)**. The repository preserves the original project phases and documentation alongside the implementation.

## Project status

Completed academic project. The codebase is retained as a portfolio and learning reference for React Native, API integration, and MongoDB-backed mobile application development.