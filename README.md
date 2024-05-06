# Your Local Time

This is a simple web page that displays your local time.

## Project Structure

- `index.html`: This is the main HTML file for the web page.
- `style.css`: This file contains all the CSS styles used in the web page.
- `script.js`: This JavaScript file contains the logic for updating and displaying the local time.

## How to Use

1. Open `index.html` in your web browser.
2. The web page will display your current local time, and it will update every second.

## Code Overview

The JavaScript code uses the `Date` object to get the current date and time. It then uses the `toLocaleTimeString` method to convert this to a string representing the local time.

This time string is then displayed in the `clock` div in the HTML. This process is repeated every second using the `setInterval` function, so the time displayed is always up-to-date.
