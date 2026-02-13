# Full-Stack E-commerce App

A minimal full-stack e-commerce starter: product catalog, cart, orders, auth, and admin panel.

## Features
- Product listing & details
- Shopping cart & checkout
- User authentication (signup/login)
- Order management
- Admin product management

## Tech stack
- Backend: Node.js, Express, REST API
- Database: PostgreSQL / MongoDB
- Frontend: React (or your preferred framework)
- Auth: JWT
- Payments: Stripe (optional)

## Quick start
1. Clone
    git clone <repo-url>
2. Backend
    cd backend
    npm install
    create .env (see sample below)
    npm run dev
3. Frontend
    cd ../frontend
    npm install
    npm start

## Example .env
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
STRIPE_KEY=your_stripe_key
PORT=5000

## Contributing
PRs and issues welcome.

## License
MIT