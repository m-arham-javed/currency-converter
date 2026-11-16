# Currency Converter Web Application

## Project Overview
A responsive **Currency Converter** built with vanilla **JavaScript**, **HTML5**, and **CSS3**. The application fetches real-time exchange rates via API integration, maps global currency codes to country flags (`codes.js`), and calculates accurate multi-currency conversions with an intuitive user interface.

## Key Features
* **Real-Time Exchange Rates:** Fetches up-to-date conversion rates asynchronously using the JavaScript Fetch API.
* **Dynamic Country Flag Mapping:** Automatically updates country flags whenever the source or target currency dropdown changes (`codes.js`).
* **Input Validation & Default Handling:** Validates user-entered amounts and gracefully defaults invalid or empty inputs to `1`.
* **Responsive Interface:** Clean, mobile-friendly card layout styled with custom CSS (`style.css`).

## Project Structure
* **`index.html`:** Semantic markup for the converter card, amount input, and currency selectors.
* **`style.css`:** Custom styling, layout alignment, and responsive design rules.
* **`app.js`:** Core conversion logic, API data fetching, and DOM manipulation.
* **`codes.js`:** Lookup dictionary mapping currency codes to country codes for flag rendering.

## Tech Stack
* **Languages:** JavaScript (ES6+), HTML5, CSS3
* **API Integration:** Fetch API / Async-Await

## Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/m-arham-javed/currency-converter.git
   cd currency-converter
