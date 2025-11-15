# SmartRent - Rental Platform

**SmartRent** is a modern rental platform where users can browse, rent, and list items across multiple categories. Built with React, TypeScript, Vite, and Tailwind CSS.

## Features

- 🎯 Browse items across multiple categories (Music, Decoration, Sports, Uni Items, Video, Other)
- 🔍 Real-time search functionality
- 📱 Fully responsive design with mobile-first approach
- 🎨 Modern dark theme with gradient accents
- 🔐 User authentication pages (Sign In/Sign Up)
- 📝 List your own items for rent
- 🎭 Category-specific detail pages with filtering
- ⚡ Fast and optimized with Vite

## Tech Stack

- **React 18** - UI Library
- **TypeScript** - Type Safety
- **Vite** - Build Tool & Dev Server
- **React Router DOM** - Client-side routing
- **Tailwind CSS** - Styling
- **Lucide React** - Icon Library

## Getting Started

### Prerequisites

- Node.js 16+ and npm

### Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd Smart-Rent

# Install dependencies
npm install

# Start development server
npm run dev
```

The application will be available at `http://localhost:5173`

## Available Routes

- `/` - Home page with hero section and categories
- `/browse` - Browse all categories
- `/category/:categoryId` - Category detail pages
  - `/category/music` - Music instruments and gear
  - `/category/decoration` - Event decor and furniture
  - `/category/sports` - Sporting equipment
  - `/category/uni` - University items
  - `/category/video` - Video and camera equipment
  - `/category/other` - Other rental items
- `/list-item` - List a new item for rent
- `/how-it-works` - Platform information
- `/signin` - User sign in
- `/signup` - User registration

## Project Structure

```
Smart-Rent/
├── src/
│   ├── assets/         # Images and static files
│   ├── components/     # Reusable components
│   │   ├── CategoryCard.tsx
│   │   ├── CategoryGrid.tsx
│   │   ├── Footer.tsx
│   │   ├── Header.tsx
│   │   └── Hero.tsx
│   ├── pages/          # Page components
│   │   ├── Browse.tsx
│   │   ├── CategoryDetail.tsx
│   │   ├── Home.tsx
│   │   ├── HowItWorks.tsx
│   │   ├── ListItem.tsx
│   │   ├── SignIn.tsx
│   │   └── SignUp.tsx
│   ├── App.tsx         # Main app component with routes
│   ├── main.tsx        # Entry point
│   └── index.css       # Global styles
├── public/             # Public assets
└── package.json
```

## Scripts

```bash
# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.
