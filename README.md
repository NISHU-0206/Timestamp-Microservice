# Timestamp Microservice

A simple full-stack JavaScript Timestamp Microservice

## 🚀 Project Overview

This microservice receives a date string or timestamp and returns a JSON response with both the Unix timestamp and UTC date string. If no date is provided, it returns the current timestamp. If the date is invalid, it returns an error message.


## 📚 Features

- Accepts a date string or Unix timestamp (in milliseconds).
- Returns JSON with:
  - `unix` timestamp (number)
  - `utc` date string (string)
- Handles invalid date inputs with an error response.
- Returns current time if no date parameter is provided.

## 🔧 Technologies Used

- Node.js
- Express.js
- CORS middleware
