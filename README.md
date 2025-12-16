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

- user registration
- user authentication
- password reset
- user account management

## API Endpoints

- `POST /api/register` - Create a new user account
- `POST /api/login` - Authenticate a user
- `POST /api/reset-password` - Reset a user's password
- `GET /api/user` - Retrieve a user's account information
- `PUT /api/user` - Update a user's account information
- `DELETE /api/user` - Delete a user's account

## License

MIT
