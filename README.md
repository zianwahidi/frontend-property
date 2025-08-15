# Property Listing Website

A modern and responsive property listing website built with React. This project features a clean and intuitive interface for browsing property listings, user authentication, and profile management.

## Features

### 1. User Authentication
- User registration with email
- Login functionality
- Google authentication option
- Protected routes for authenticated users

### 2. Property Listing
- Grid view of property listings with detailed information
- Property cards showing:
  - Property images
  - Location with verification badge
  - Property type (Rumah, Apartement, etc.)
  - Status (New, Second)
  - Price
  - Property details (Land area, Building area, Bedrooms)
  - Bookmark functionality
  - Book button for interested users

### 3. Search & Filter
- Search bar for property search
- Advanced filtering options:
  - Status filter (New, Second)
  - Location filter (Bekasi, Jakarta, Bandung, Bogor)
  - Property type filter (Rumah, Apartement, Ruko, Hotel)
  - Price range filter
- Sort options:
  - Most Relevant
  - Newest
  - Price (Low to High)
  - Price (High to Low)

### 4. User Profile
- Profile dashboard with:
  - Profile picture
  - Personal information
  - Location
  - Profile status indicator
  - Progress tracking
- Tabs for:
  - About
  - Projects
  - Properties
  - Activities
- Profile editing functionality
- Industry and University information sections

### 5. Responsive Design
- Fully responsive layout
- Mobile-friendly navigation
- Adaptive property grid
- Responsive filters and search

## Technologies Used

- **Frontend Framework**: React.js
- **Routing**: React Router v6
- **Styling**: CSS3 with modern features
- **State Management**: React Hooks (useState, useEffect)
- **Authentication**: JWT based authentication
- **HTTP Client**: Fetch API
- **Build Tool**: Vite

## Project Structure

```
frontend-property/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   ├── react.svg
│   │   └── property images
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   └── Profile.jsx
│   ├── services/
│   │   └── api.js
│   ├── styles/
│   │   ├── home.css
│   │   ├── login.css
│   │   ├── register.css
│   │   └── profile.css
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── vite.config.js
```

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone [repository-url]
cd frontend-property
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm run dev
# or
yarn dev
```

## Features Implementation Details

### Authentication Flow
- User registration with email validation
- JWT token storage in localStorage
- Protected route implementation
- Automatic redirect to login for unauthenticated users

### Property Listing
- Dynamic property card generation
- Image optimization for faster loading
- Lazy loading implementation for better performance
- Interactive bookmark functionality

### Search & Filter System
- Real-time search functionality
- Multiple filter combination support
- Price range slider with min/max values
- Sort implementation with multiple criteria

### Profile Management
- Profile image upload capability
- Editable profile information
- Progress tracking system
- Activity logging

## Styling Guide

The project uses a consistent color scheme:
- Primary Color: #FF006E
- Secondary Color: #2563EB
- Text Colors: 
  - Primary: #111827
  - Secondary: #4B5563
  - Light: #6B7280
- Background Colors:
  - Main: #f3f4f6
  - Cards: #ffffff

## Future Improvements

1. **Performance Optimization**
   - Implement image lazy loading
   - Add service worker for offline capability
   - Optimize bundle size

2. **Feature Additions**
   - Add property comparison functionality
   - Implement favorite properties list
   - Add map integration for property location
   - Enhanced filter options

3. **UI/UX Improvements**
   - Add more animations and transitions
   - Implement dark mode
   - Add more interactive elements

