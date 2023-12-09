# React SPA Project

## Overview

Welcome to the React SPA Project!
This Single Page Application (SPA) is built with React and incorporates advanced techniques and technologies to create a dynamic and feature-rich web application.

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

### 1. React Router for Navigation

- Utilizes [`react-router-dom`](https://reactrouter.com/web/guides/quick-start) for seamless navigation within the SPA.
- Dynamic routes enable the display of specific city details using parameters.

### 2. Lazy Loading and Code Splitting

- Implements lazy loading with the [`lazy`](https://reactjs.org/docs/code-splitting.html#reactlazy) function and [`Suspense`](https://reactjs.org/docs/react-api.html#suspense) component for optimal bundle size and improved performance.
- Lazily loads components such as Homepage, Product, Pricing, Login, AppLayout, and PageNotFound.

### 3. Context API and State Management

- Utilizes the React Context API for efficient state management.
- `CitiesProvider` and `AuthProvider` are custom context providers managing city-related state and fake authentication, respectively.

### 4. Fake Authentication

- Simulates authentication using the `FakeAuthContext` for development purposes.

### 5. Protected Routes

- Implements the `ProtectedRoute` component to secure certain routes, ensuring authentication before accessing specific parts of the application.

### 6. Leaflet Library for Maps

- Integrates the [Leaflet](https://leafletjs.com/) library for interactive maps, likely in the `City` component.

### 7. Custom Hooks and Providers

- Demonstrates the use of custom hooks and providers, including `CitiesProvider` and `AuthProvider`.

### 8. Geolocation

- Incorporates geolocation functionality, possibly for displaying maps and location-specific information.

### 9. Optimizations

- Implements optimization techniques such as `useMemo` and `useCallback` for improved performance.

### 10. Programmatic Navigation

- Achieves programmatic navigation using the `Navigate` component from React Router.

### 11. CSS Modules

- Utilizes CSS Modules to locally scope styles in React components, preventing style conflicts.
