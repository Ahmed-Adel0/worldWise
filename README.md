# WorldWise - Your Adventure Tracker

## Overview

Welcome to WorldWise, your go-to platform for tracking and sharing your travel adventures! This Single Page Application (SPA) is built with React, leveraging advanced techniques and technologies to provide a dynamic and feature-rich web experience. Keep a digital record of your journeys, explore new cities, and share your wanderlust with friends.

## Table of Contents

1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)

## Technologies Used

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/)
- [Leaflet](https://leafletjs.com/)
- Context API
- CSS Modules
- Other React Hooks (useMemo, useCallback, useReducer)

## Key Features

### 1. React Router for Seamless Navigation

- Utilizes `react-router-dom` for smooth and intuitive navigation within the application.
- Dynamic routes enhance the user experience by allowing the display of specific city details.

### 2. Lazy Loading and Code Splitting

- Implements lazy loading and code splitting to optimize initial load times and improve overall performance.
- Components are loaded on-demand, ensuring a responsive and efficient user interface.

### 3. Context API and State Management

- Leverages the React Context API for efficient state management.
- Custom context providers (`CitiesProvider` and `AuthProvider`) enhance the application's ability to manage city-related data and simulate user authentication.

### 4. Authentic Adventure Simulation

- Experience the thrill of tracking your adventures with simulated authentication using the `FakeAuthContext`.
- Test WorldWise's features without the need for a live authentication server during development.

### 5. Protected Routes for Enhanced Security

- Implements the `ProtectedRoute` component to secure specific routes, ensuring users are authenticated before accessing certain parts of the application.
- Safeguard your personal travel data and ensure a secure user experience.

### 6. Leaflet Library for Interactive Maps

- Integrates the Leaflet library to provide an interactive and visually appealing world map.
- Track your footsteps into every city imaginable and create a visual representation of your travel experiences.

### 7. Custom Hooks and Providers

- Demonstrates the power of custom hooks and providers, such as `useMemo` and `useCallback`, to optimize performance and enhance functionality.
- Enhance your development experience with reusable and efficient code patterns.

### 8. Geolocation for Location-specific Experiences

- Utilizes geolocation functionality to enhance the mapping experience.
- Display maps and location-specific information, adding an extra layer of detail to your adventures.

### 9. Programmatic Navigation for Intuitive User Journeys

- Achieves programmatic navigation using the `Navigate` component from React Router.
- Seamlessly guide users through the application, providing an intuitive and user-friendly journey.

### 10. CSS Modules for Stylish Components

- Utilizes CSS Modules to locally scope styles in React components.
- Prevents style conflicts and ensures a consistent and visually appealing user interface.
