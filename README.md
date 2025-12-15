# e

Backend API for e

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/Malleswar-249/E-COMMERCE-WEBSITE))

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

- User management
- Authentication
- Data storage

## API Endpoints

- `POST /api/register` - Register a new user
- `POST /api/login` - Log in to the application
- `POST /api/password_reset` - Reset user password
- `GET /api/profile` - View user profile
- `PUT /api/profile` - Update user profile
- `GET /api/users` - View all users

## License

MIT
