# MovieBox - BookMyShow-style JavaScript Project

A frontend-only movie ticket booking project built with HTML, CSS and vanilla JavaScript.

## Features

- Movie cards
- Movie search
- Movie details
- Date selection
- Theatre selection
- Showtime selection
- Interactive 10 x 10 seat map
- Occupied and selected seats
- Ticket price calculation
- Booking summary
- Simulated payment/confirmation
- Unique booking ID
- Booking history using localStorage
- Responsive design
- Automatic closing of the booking modal after successful booking

## How to run

1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Choose a movie.
4. Select date, theatre and showtime.
5. Select seats.
6. Confirm the booking.
7. The confirmation modal closes automatically after 4 seconds.

## Important note about window.close()

This project closes the **booking modal**, not the browser tab itself.

Browsers generally prevent normal webpages from closing tabs that the user opened manually. If you want a separate popup window to close itself, that popup should normally have been opened by JavaScript using `window.open()`.

## Technologies

- HTML5
- CSS3
- JavaScript (ES6)
- localStorage

## Project structure

bookmyshow_style_app/
  index.html
  style.css
  script.js
  README.md

The poster URLs are demo images. For a real application, replace them with your own movie images or an approved movie-data/image API.
