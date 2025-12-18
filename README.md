# e

Backend API for e

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/HimaShankarReddyEguturi/Designecommerceproductui.git))

## Project Structure

```
e/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- User registration and login
- User profile management
- User-to-user relationships
- Password reset

## API Endpoints

- `POST /api/register` - Create a new user account
- `POST /api/login` - Log in to an existing user account
- `GET /api/profile` - Get the current user's profile information
- `PUT /api/profile` - Update the current user's profile information
- `GET /api/users` - Get a list of all users
- `GET /api/users/{username}` - Get a specific user's profile information

## License

MIT
