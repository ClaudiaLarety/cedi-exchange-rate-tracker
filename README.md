# Cedi Exchange Rate Tracker

A web page that shows the live US dollar to Ghana cedi rate, a 30-day history chart, and a simple 7-day trend forecast.

**Live demo:** https://claudialarety.github.io/cedi-exchange-rate-tracker/


## Features
- Live USD to GHS rate from the FXRatesAPI free API
- 30-day history chart built with Chart.js
- 7-day forecast using a straight-line (linear regression) trend
- Error message if the data can't be loaded

## How to run
Open `index.html` in any browser. No install needed.

## How the forecast works
A straight line is fitted through the last 30 daily rates using least squares, then extended 7 days. It shows the recent direction only. It can't predict sudden moves, so it is not financial advice.

## Built with
HTML, JavaScript, Chart.js, FXRatesAPI

## Roadmap
- Choose other currencies
- Choose the time range (7, 30 or 90 days)

## Author
Claudia Lartey