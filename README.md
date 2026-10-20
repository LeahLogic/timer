# Digital Clock

A simple digital clock application built with React and Vite. The application displays the current local time and updates automatically every second using React class components and lifecycle methods.

## Features

- **Real-Time Clock:** Displays the current local time.
- **Automatic Updates:** Refreshes the displayed time every second.
- **Local Time Format:** Uses the browser's locale settings to format the time.
- **Minimalist Interface:** A clean digital clock display with a simple background.

## Technologies

- React
- JavaScript (ES6+)
- HTML5
- CSS3
- Vite

## Project Structure

The application uses a React class component to manage and update the displayed time.

- `App.jsx` — Main application component that renders the clock.
- `Clock.jsx` — Manages the current time, updates the display, and handles component lifecycle methods.
- `App.css` — Defines the visual styling of the application.

## Getting Started

Clone the repository and install the required dependencies.

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL displayed in the terminal to view the application.

## Implementation

The clock uses React's `Component` class and maintains the current time in its state.

The `componentDidMount()` lifecycle method starts an interval that updates the time every second. The `componentWillUnmount()` method clears the interval to prevent unnecessary background execution.

The current time is formatted using JavaScript's `toLocaleTimeString()` method.

## About

This project demonstrates React class components, state management, lifecycle methods, and working with JavaScript's Date API.

## Author

Leah