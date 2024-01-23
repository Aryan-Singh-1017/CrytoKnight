# CryptoKnight

CryptoKnight is a React application that provides information about cryptocurrencies, including live data, news, and exchange details.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Environment Variables](#environment-variables)
- [Available Scripts](#available-scripts)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

CryptoKnight is a cryptocurrency information portal built using React and various libraries and tools. The application allows users to explore real-time data about cryptocurrencies, read the latest news, and get insights into cryptocurrency exchanges.

## Features

- **Live Cryptocurrency Data:** View real-time information about various cryptocurrencies.
- **Crypto News:** Read the latest news related to cryptocurrencies.
- **Exchange Details:** Explore details about different cryptocurrency exchanges.
- **Responsive Design:** The application is designed to work seamlessly across various devices.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/CryptoKnight.git
    ```

2. Navigate to the project directory:

    ```bash
    cd CryptoKnight
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

## Usage

1. Start the development server:

    ```bash
    npm start
    ```

2. Open your browser and visit `http://localhost:3000` to view the application.

## Folder Structure

The project structure is organized as follows:

- `src/`: Contains the application source code.
  - `components/`: React components used in the application.
  - `services/`: Services for fetching data from external APIs.
  - `styles/`: Stylesheets for styling the application.
  - `App.js`: Main component that sets up the application routes.
  - ...

- `public/`: Contains static assets and the `index.html` file.

- `.env.example`: Example environment variable configuration. Create a `.env` file based on this template.

## Environment Variables

The application uses the following environment variables:

- `REACT_APP_RAPIDAPI_KEY`: API key for RapidAPI (used for crypto data and news).
- `REACT_APP_CRYPTO_RAPIDAPI_HOST`: RapidAPI host for cryptocurrency data.
- `REACT_APP_CRYPTO_API_URL`: Base URL for the cryptocurrency API.
- `REACT_APP_NEWS_API_URL`: Base URL for the news API.
- `REACT_APP_NEWS_RAPIDAPI_HOST`: RapidAPI host for news data.

Make sure to create a `.env` file with these variables before running the application.

## Available Scripts

- `npm start`: Starts the development server.
- `npm run build`: Builds the production-ready application.
- `npm test`: Runs tests.

## Dependencies

- `@ant-design/icons`: Ant Design icons.
- `@reduxjs/toolkit`: Redux Toolkit for state management.
- `axios`: HTTP client for making API requests.
- `chart.js`: Chart.js for displaying charts.
- `react`: React library.
- ...

## Contributing

Contributions are welcome! If you have any improvements or new features to suggest, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
