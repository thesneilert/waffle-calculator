
# Waffle Christmas Decorations Pricing Calculator

This is a simple web application that calculates the price of waffle-themed Christmas decorations based on quantity. The app has a user-friendly interface with buttons representing quantities from 1 to 30, and prices are calculated dynamically as you click on each quantity.

## Features

- **Dark Mode Design**: The application features a sleek dark mode interface.
- **Responsive Layout**: A grid of buttons makes it easy to select quantities from 1 to 30.
- **Dynamic Pricing**: Prices update dynamically as you select quantities.
  - Price rules:
    - 1 item costs 150 kr.
    - 2 items cost 250 kr.
    - Every 3 items cost 300 kr.
    - For quantities between multiples of 3, the price follows the pattern:
      - 1 additional item adds 150 kr.
      - 2 additional items add 250 kr.

## How to Use

1. Open the [page](https://thesneilert.github.io/waffle-calculator/) in a web browser.
2. Click on the quantity buttons (1 to 30) to calculate the price of waffle decorations.
3. The price will be displayed in the center box.

## Code Structure

- The app uses JavaScript to calculate and display prices.
- The buttons for quantities 4 to 30 are generated dynamically using JavaScript for convenience.
- Prices are calculated using predefined logic based on quantity.

## Example Calculation

- For 1 item: 150 kr
- For 2 items: 250 kr
- For 3 items: 300 kr
- For 4 items: 450 kr (300 kr for 3 items + 150 kr for 1 item)
