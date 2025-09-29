# Transpara Tech

A modern React application built with Vite for faster development and optimized production builds.

## Features

- ⚡️ **Lightning Fast Dev Experience** - Powered by Vite for instant server start and hot module replacement
- 🔄 **React** - Using the latest version of React with functional components and hooks
- 🎨 **Modern CSS** - Clean styling with light/dark mode support
- 📦 **Optimized Bundle** - Efficient bundle size for production
- 🧹 **ESLint** - Modern linting setup for code quality

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install
# or
yarn
```

### Development

```bash
# Start the development server
npm run dev
# or
yarn dev
```

The app will be available at [http://localhost:5173](http://localhost:5173)

### Building for Production

```bash
# Create a production build
npm run build
# or
yarn build
```

### Preview Production Build

```bash
# Preview the production build locally
npm run preview
# or
yarn preview
```

## Project Structure

```
transpara-tech/
├── public/              # Static assets
│   └── vite.svg         # Vite logo
├── src/                 # Source code
│   ├── assets/          # Project assets
│   │   └── react.svg    # React logo
│   ├── App.css          # App component styles
│   ├── App.jsx          # Main App component
│   ├── index.css        # Global styles
│   └── main.jsx         # Entry point
├── eslint.config.js     # ESLint configuration
├── package.json         # Project dependencies and scripts
├── README.md            # Project documentation
└── vite.config.js       # Vite configuration
```

## Customizing

### Adding Dependencies

```bash
npm install <package-name>
# or
yarn add <package-name>
```

### ESLint Configuration

Edit `eslint.config.js` to customize the linting rules.

### Vite Configuration

Edit `vite.config.js` to customize the build process, add plugins, or configure other Vite options.
