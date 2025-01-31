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
const response = await fetch(`https://v6.exchangerate-api.com/v6/589f59147a429e2ee416876d/latest/${fromCur.value}`);
![Screenshot (617)](https://github.com/user-attachments/assets/9e6fd310-6218-40b8-9350-c8f48837f4c8)
![Screenshot (618)](https://github.com/user-attachments/assets/668f141d-b54d-4c05-acf9-a11dab1a7900)
