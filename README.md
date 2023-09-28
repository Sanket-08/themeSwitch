# Theme Switcher React App

## Overview

This is a simple React application that demonstrates theme switching functionality. Users can toggle between light and dark themes, and the application dynamically adjusts its appearance based on the selected theme.

## Features

- **Theme Switching**: Users can switch between "light" and "dark" themes, which affects the entire application's appearance.

- **Card Component**: The app includes a sample product card component that showcases how theme-specific styling can be applied.

## Components

### `App.js`

- Manages the theme mode state (`light` or `dark`).
- Uses React context to provide theme-related data to child components.
- Includes a layout with a theme switcher button and a sample card component.

### `Card.js`

- Represents a product card component with dynamic theming.
- Utilizes conditional classes to adjust styles based on the selected theme.
- Displays product information, including an image, title, rating stars, price, and an "Add to cart" button.

### `ThemeBtn.js`

- Provides a button to toggle between light and dark themes.
- Accesses the theme-related context using a custom hook.
- Adjusts the appearance of the button and checkbox based on the current theme.



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
