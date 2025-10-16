Here are precise README files for both frontend and backend:

## Frontend

```markdown
# RecipeApp - React Native Frontend

## Project Structure
```
src/
├── assets/          # Static files (images, icons, fonts)
├── components/      # Reusable UI components
├── screens/         # App screens/pages
├── navigation/      # Navigation configuration
├── services/        # API calls and external services
├── store/           # State management (Redux)
├── hooks/           # Custom React hooks
├── utils/           # Helper functions and constants
└── styles/          # Global styles and themes
```

## Setup
1. `npm install`
2. `npx expo start`
3. Scan QR code with Expo Go app

## Features
- User authentication
- Recipe browsing and search
- Favorite recipes
- Create and edit recipes
- Step-by-step cooking guide

## Environment Variables
Create `.env` file:
```
API_URL=your_backend_url
```

## Scripts
- `npm start` - Start development server
- `npm run android` - Run on Android
- `npm run ios` - Run on iOS
- `npm run build` - Build for production
```