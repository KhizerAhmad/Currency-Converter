# 💱 Currency Converter

A simple and responsive currency converter built with modern web technologies. Select currencies, enter an amount, and instantly get real-time exchange rates using a public API.

---

## What it does

* Convert between different currencies in real time
* Select **from and to currencies**
* Enter amount and get instant conversion
* Fetches live exchange rates from a public API
* Clean and responsive UI

---

## Why I built this

This project was built to practice working with real-world APIs — especially handling asynchronous requests, updating UI based on dynamic data, and managing user input efficiently. It also helped reinforce concepts like state handling and API error handling in frontend development.

---

## Tech Stack

| Technology         | Usage                         |
| ------------------ | ----------------------------- |
| JavaScript / React | Core logic and UI             |
| HTML & CSS         | Structure and styling         |
| Exchange Rate API  | Fetch real-time currency data |
| Fetch API / Axios  | API requests                  |

---

## How to run it locally

```bash
git clone https://github.com/KhizerAhmad/Currency-Converter.git
cd Currency-Converter
```

If it's a React project:

```bash
npm install
npm start
```

If it's a simple JavaScript project:

* Open `index.html` in your browser

---

## Project Structure

```
Currency-Converter/
│
├── public/
├── src/
│   ├── components/      # Currency selectors, input fields, result display
│   ├── App.js
│   └── styles.css
├── index.html
├── package.json
└── README.md
```

---

## API Used

This app uses a free exchange rate API to fetch real-time currency data.

**Example request:**

```
https://api.exchangerate-api.com/v4/latest/USD
```

---

## Features at a glance

* **Real-time conversion** — always up-to-date exchange rates
* **Currency selection** — convert between multiple currencies
* **Instant calculation** — updates as you type
* **Simple UI** — easy to use and clean layout
* **Responsive design** — works across devices

---

## Available Scripts (if React)

```bash
npm start        # Run development server
npm run build    # Build for production
```

## Author

**Khizer Ahmad** — built this to practice API integration, handling real-time data, and improving frontend development skills.

Feel free to fork it and add features like historical rates, charts, or currency trends.

---
