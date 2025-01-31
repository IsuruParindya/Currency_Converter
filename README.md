# Currency Converter

A simple web-based currency converter that allows users to convert values between different currencies in real-time.

## Features
- Convert between multiple currencies.
- Fetches real-time exchange rates from an API.
- User-friendly interface.
- Supports multiple international currencies.

## Technologies Used
- HTML, CSS, JavaScript
- Fetch API (to get exchange rates)
- Open Exchange Rates / Any Free Currency API

## How to Use
1. Enter the amount you want to convert.
2. Select the source currency.
3. Select the target currency.
4. Click the "Convert" button to get the converted amount.

## Example API Request
```javascript
fetch(`https://api.exchangerate-api.com/v4/latest/USD`)
  .then(response => response.json())
  .then(data => console.log(data));
