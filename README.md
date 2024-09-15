# Uplines CashBack Calculator

## Description

The Uplines CashBack Calculator is a web-based tool designed to calculate and visualize CashBack shares for members in a multi-level marketing structure. It allows users to input invoice amounts, select invoiced members, and set CashBack rates to generate detailed breakdowns of earnings and distributions.

## Features

- Dynamic member hierarchy setup with initial amounts and parent selection
- CashBack calculation based on invoice amount and vendor CashBack rate
- Visualization of member hierarchy and earnings
- Detailed results display including individual member allocations
- Dark mode support for better viewing experience in low-light conditions

## Technologies Used

- HTML5
- JavaScript
- Tailwind CSS (via CDN)

## How to Use

1. Open `index.html` in a web browser.
2. Set up the initial amounts and parent relationships for each member in the "Initial Amounts and Parent Selection" section.
3. Enter the invoice amount, select the invoiced member, and set the vendor CashBack rate in the "Calculate Members CashBack" section.
4. Click the "Calculate" button to generate results.
5. View the detailed breakdown of CashBack distribution and the visual representation of the member hierarchy.
6. Toggle between light and dark modes using the moon icon in the top-right corner.

## Customization

- Modify the number of members by changing the loop in the JavaScript code.
- Adjust the admin fee rate and member share rate in the `calculateCommission` function.
- Customize the styling by modifying the Tailwind CSS classes or adding custom CSS.

## License

MIT

## Author

Murad Alwan

## Acknowledgments

- Tailwind CSS for the utility-first CSS framework

