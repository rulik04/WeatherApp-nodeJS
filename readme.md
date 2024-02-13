# ClimaCast

ClimaCast is a weather forecast application that provides current weather information, 5-day forecasts, and air quality data for a specified city. It also includes additional details such as sunrise, sunset, humidity, wind, and more.

## Table of Contents
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Search for a City](#search-for-a-city)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Environment Variables (.env)](#environment-variables)
- [Admin Credentials for Website Login](#admin-credentials-for-website-login)


## Getting Started

### Prerequisites
Make sure you have the following software installed on your machine:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/rulik04/WeatherApp-nodeJS.git
   ```
2. Navigate to the project directory.
   ```bash
   cd WeatherApp
   ```
3. Install dependencies.
   ```bash
   npm install
   ```

## Usage

### Search for a City
To get weather information for a different city:
1. Enter the desired city name in the search input.
2. Click the "Get Weather" button or press Enter.
3. The application will fetch and display the weather details for the specified city.

## Features
- Current weather information (temperature, description, icon, date, location, time, etc.).
- 5-day forecast with temperature and date details.
- Air quality information (SO2, NO2, O3, PM2.5).
- Highlights such as sunrise, sunset, humidity, clouds, wind, and feels-like temperature.
- Map display with a marker for the selected city.

## Technologies Used
- HTML
- CSS (Bootstrap)
- JavaScript
- Node.js (Express)
- OpenWeatherMap API
- TimezoneDB API
- Google Maps JavaScript API



### Environment Variables

Before running the application, ensure you have set up the necessary environment variables by creating a `.env` file in the root directory of the project. The `.env` file should contain the following variables:

```plaintext
PORT=3000
```

Make sure to replace `3000` with the desired port number if needed.

### Admin Credentials for Website Login

To access the admin features of the website, you can use the following credentials:

- **Username:** Rulan
- **Password:** 55810579
