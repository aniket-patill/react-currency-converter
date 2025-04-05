# react-currency-converter

A web-based currency converter built with React and Vite. This project demonstrates a simple UI for converting amounts between currencies using live exchange rate data fetched from an external API.

## Overview

This project provides a minimalist currency converter application. Users can input an amount, select source and target currencies, and convert the amount based on live exchange rates retrieved from an external service. The app makes use of:

- [React](https://reactjs.org/) for building the user interface.
- [Vite](https://vitejs.dev/) as the build tool for fast development and optimized production builds.
- [TailwindCSS](https://tailwindcss.com/) for styling.

## Features

- **Real-time Currency Conversion:** Fetches current exchange rates using [`useCurrencyInfo`](./src/hooks/useCurrencyInfo.js).
- **Responsive UI:** Styled with TailwindCSS for a modern and adaptive design.
- **Component Reusability:** Incorporates a reusable [`InputBox`](./src/components/InputBox.jsx) component for handling inputs.
- **State Management:** Utilizes React's state hooks to manage conversion data and user inputs.
- **Hot Module Replacement:** Vite’s fast refresh feature for seamless development.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/currency-converter.git
   cd currency-converter
   ```

2. Install dependencies:
   
   ```bash
   npm install
   ```

3. Start the development server with:
  
  ```bash
   npm run dev
   ```

This command starts Vite in development mode with hot module replacement enabled.

## Project Structure

```bash
currencyConverter/
├── index.html
├── package.json
├── README.md
├── vite.config.js
├── tailwind.config.js
├── .gitignore
└── src
    ├── main.jsx
    ├── index.css
    ├── App.jsx
    ├── App.css
    ├── components
    │   ├── InputBox.jsx
    │   └── index.js
    └── hooks
        └── useCurrencyInfo.js
```


