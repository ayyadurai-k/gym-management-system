# Gym Management System

A full-stack MERN application designed to streamline gym administration across multiple branches. The platform centralizes member management, product catalogs, and branch operations into a single dashboard — giving gym owners the ability to manage their entire business and pull detailed reports with a single click.

## Overview

Running a gym chain involves coordinating memberships, tracking inventory, managing multiple branches, and producing operational reports for owners. This project consolidates all of that into one administrative tool, replacing scattered spreadsheets and disconnected systems with a unified web platform.

Built end-to-end as part of my full-stack development practice, the system reflects real-world admin software patterns — role-based dashboards, CRUD-heavy workflows, and report generation that owners can act on immediately.

## Features

- 🏢 **Multi-branch management** — Manage memberships, staff, and products across multiple gym branches from one dashboard
- 👥 **Member lifecycle** — Member registration, membership plans, renewals, and history tracking
- 📦 **Product catalog** — Track supplements, equipment, and merchandise inventory
- 📊 **One-click owner reports** — Detailed analytics on memberships, revenue, and branch performance generated instantly
- 🔐 **Role-based access** — Separate admin, branch manager, and staff permissions
- 📱 **Responsive UI** — Works on desktop and tablet for on-the-floor admin use

## Tech Stack

| Layer | Tech |
|---|---|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Auth | JWT-based authentication |

## Project Structure

```
.
├── backend/      # Node.js + Express API
│   ├── models/   # MongoDB schemas
│   ├── routes/   # API endpoints
│   └── server.js
├── frontend/     # React.js client
│   ├── src/
│   ├── public/
│   └── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 16+
- MongoDB (local or Atlas)
- npm or yarn

### Setup

```bash
# Clone the repo
git clone https://github.com/ayyadurai-k/gym-management-system.git
cd gym-management-system

# Install backend dependencies
cd backend
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your MongoDB URI and JWT secret

# Start the backend
npm run dev

# In a new terminal, install and start the frontend
cd ../frontend
npm install
npm start
```

The backend runs on `http://localhost:5000` and the frontend on `http://localhost:3000`.

## Author

**K Ayyadurai** — Full Stack & DevOps Engineer
[GitHub](https://github.com/ayyadurai-k) · [Email](mailto:kmayyadurai286@gmail.com)
