# Item Catalog

A modern, responsive web application for managing and browsing a catalog of items. Built with React, TypeScript, and Material-UI.

![Item Catalog Screenshot](public/screenshot.png)

## Features

- Browse items in a responsive grid layout
- View item details with image carousel
- Add new items with multiple images
- Search and filter items
- Responsive design that works on all devices
- Modern UI with Material-UI components

## Technologies Used

- React 18 with TypeScript
- Vite for fast development and building
- Material-UI (MUI) for UI components
- React Router for navigation
- React Hook Form for form handling
- Yup for form validation
- LocalStorage for data persistence

## Getting Started

### Prerequisites

- Node.js (v16 or later)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sathvikcoderr02/itemCatalog.git
   cd itemCatalog
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Project Structure

```
src/
├── components/     # Reusable UI components
├── context/        # React context providers
├── hooks/          # Custom React hooks
├── pages/          # Page components
├── services/       # API and service integrations
├── types/          # TypeScript type definitions
├── utils/          # Utility functions
├── App.tsx         # Main application component
└── main.tsx        # Application entry point
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
    ...reactDom.configs.recommended.rules,
  },
})
```
