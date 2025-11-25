# Spy

A React learning project - a landing page template built while learning React fundamentals.

## About

This is a React-based landing page template created as a learning exercise. The project demonstrates basic React concepts including:

- Component-based architecture
- React hooks (useState)
- CSS styling and responsive design
- Project organization with modular components

## Project Structure

```
src/
├── App.js              # Main application component
├── App.css             # Main app styles
├── index.js            # React entry point
├── index.css           # Global styles and CSS variables
└── components/
    ├── index.js        # Component exports
    ├── navbar/         # Navigation bar with mobile menu toggle
    ├── header/         # Header section
    ├── features/       # Features section
    ├── download/       # Download section
    ├── subscribe/      # Subscribe section
    ├── faq/            # FAQ section
    └── footer/         # Footer section
```

## Features

- **Responsive Navbar**: A navigation bar with a mobile menu toggle using React state
- **Modular Components**: Organized component structure with separate CSS files
- **CSS Variables**: Global theming with CSS custom properties
- **Poppins Font**: Google Fonts integration

## Tech Stack

- React 17
- Create React App
- React Icons

## Getting Started

### Prerequisites

- Node.js (version 14 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production

## Note

This was an early React learning project. Most components are placeholder implementations, with the Navbar being the most complete component featuring a functional mobile menu toggle.
