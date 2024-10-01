# Digital Clock Project

This project is a simple digital clock that displays the current time in hours, minutes, and seconds, along with the AM/PM indicator. The clock updates every second and is styled to fit in the center of the screen with a clean, modern design.

## Features

- **Current Time Display**: Shows hours, minutes, seconds, and AM/PM.
- **Real-time Updates**: Automatically updates every second.
- **Responsive Design**: The clock is centered on the screen with a visually appealing background and easy-to-read text.

## Project Structure

The project consists of three files:

1. `index.html` – The main structure of the web page.
2. `style.css` – Styling for the layout, background, and clock design.
3. `index.js` – JavaScript logic to update the clock every second.

## How to Use

1. Open `index.html` in your web browser.
2. The current time will automatically display and update in real-time.

## Files Overview

### HTML (index.html)
This file contains the structure of the web page, including the container for the clock display.

### JavaScript (index.js)
This script handles the logic for updating the time every second. It retrieves the current time using the `Date()` object, formats it into a 12-hour format with AM/PM, and displays the result on the screen.

### CSS (style.css)
The CSS file styles the clock, including background settings and text appearance. It uses flexbox to center the clock on the page, with a blurred backdrop effect to enhance readability against a background image.

## Example Usage

1. The time starts in `hh:mm:ss AM/PM` format.
2. The clock will update every second, showing the current time.

## Future Enhancements

- Add support for changing the time zone.
- Include a toggle to switch between 12-hour and 24-hour formats.
- Allow customization of the clock’s appearance through user input (e.g., color, font size).

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Run

Simply clone the repository or download the files and open `index.html` in any modern web browser. No additional setup or installation is required.

