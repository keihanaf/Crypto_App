# Crypto App

<img src="https://user-images.githubusercontent.com/74038190/212257467-871d32b7-e401-42e8-a166-fcfd7baa4c6b.gif" width="100">

## Description
Crypto App is a React-based web application that displays up-to-date information about cryptocurrencies. Using the CoinGecko API, it presents a list of top cryptocurrencies along with their prices, price changes, and trading volumes.

<h3><a href="https://crypto-app-plum-mu.vercel.app/">View Crypto App</a></h3>

## Features
- Display a list of top cryptocurrencies
- Search for specific cryptocurrencies
- Show price charts for each cryptocurrency
- Option to change currency (USD, EUR, JPY)
- Pagination to view more cryptocurrencies
- Responsive and attractive user interface

## Technologies
- React.js
- CSS Modules
- Recharts (for chart display)
- CoinGecko API

## Installation and Setup

Follow these steps to run the project on your local machine:

1. Clone the repository:
   ```
   git clone https://github.com/keihanaf/Crypto_App.git
   ```

2. Navigate to the project directory:
   ```
   cd Crypto_App
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Run the project:
   ```
   npm run dev
   ```

5. Open your browser and go to `http://localhost:5173`.

## Project Structure

- `src/components/modules`: Contains detailed components like Chart, Pagination, Search, and TableCoin
- `src/components/templates`: Contains main page components like HomePage
- `src/layouts`: Contains the Layout component for overall page structure
- `src/services`: Contains functions related to API requests
- `src/helpers`: Contains helper functions like data conversion
- `src/assets`: Contains static files such as images

## How to Use

1. On the main page, you'll see a list of top cryptocurrencies.
2. Use the search box to find a specific cryptocurrency.
3. Click on a cryptocurrency's symbol to view its price chart.
4. You can switch the currency between USD, EUR, and JPY.
5. Use the pagination buttons at the bottom of the page to view more cryptocurrencies.

## API Used

This project uses the CoinGecko API, one of the largest and most reliable sources of cryptocurrency data.

API Link: [https://www.coingecko.com/en/api/documentation](https://www.coingecko.com/en/api/documentation)

### CoinGecko API Features:
- Access to data for over 10,000 cryptocurrencies
- Real-time updates of prices and market information
- Ability to retrieve historical data
- Support for multiple fiat currencies
- Rate limit: 10-50 requests per minute (depending on account type)

### Important Notes:
- An API key is required to use this API, which is set in the `src/services/cryptoApi.js` file.
- Please be mindful of the API usage limits and use it responsibly.
- For commercial projects or high-volume requests, it's recommended to use paid versions of the API.

### Main API Functions in the Project:
- `getCoinList`: Retrieve the list of cryptocurrencies
- `searchCoin`: Search for cryptocurrencies
- `marketChart`: Get price chart data

For more information and complete API details, please refer to the official CoinGecko documentation.

## Languages and Tools

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,javascript,vite,css,vscode" />
  </a>
</p>

## Developer

This project was developed with love by Keihan.

## License

This project is released under the MIT License.
