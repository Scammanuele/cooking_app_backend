# RecipeApp - Node.js Backend

## Project Structure
```
backend/
├── src/
│   ├── controllers/ # Request handlers
│   ├── models/      # Database schemas
│   ├── routes/      # API endpoints
│   ├── middleware/  # Custom middleware
│   ├── config/      # Configuration files
│   ├── utils/       # Helper functions
│   └── services/    # Business logic
├── uploads/         # File storage
└── tests/           # Test files
```

## Setup
1. `npm install`
2. Create `.env` file (see Environment Variables)
3. `npm run dev` - Start development server

## Environment Variables
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url
```

## API Endpoints
- `POST /api/auth/login` - User login
- `POST /api/auth/register` - User registration
- `GET /api/recipes` - Get all recipes
- `POST /api/recipes` - Create new recipe
- `PUT /api/recipes/:id` - Update recipe
- `DELETE /api/recipes/:id` - Delete recipe

## Scripts
- `npm run dev` - Start dev server with nodemon
- `npm start` - Start production server
- `npm test` - Run tests
```