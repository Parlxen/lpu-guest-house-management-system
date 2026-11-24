# LPU Guest House Management System

A front-end project for a Lovely Professional University guest house and visiting parent room booking experience. It presents room options, an availability calendar, a booking form, and an estimated charge summary.

## Features

- Browse Standard Double, Executive AC, and VIP room options.
- Select stay dates and view the demo availability calendar.
- Enter visiting parent or guardian and LPU student details.
- Choose an optional meal plan and calculate estimated stay charges.
- Review a booking confirmation dialog after submitting the form.
- Responsive layout for desktop and mobile screens.

## Run locally

No build tools or dependencies are required. Open `index.html` directly in a browser, or serve the project directory with any static web server. For example, with Python installed:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Project files

- `index.html` — page structure, embedded page styles, booking form, and confirmation dialog.
- `style.css` — shared stylesheet.
- `script.js` — calendar, date handling, charge calculation, and form submission behavior.

## Demo limitations

This is a client-side demonstration. Availability dates and pricing are sample data, and submitted bookings are not sent to a server or stored persistently. Confirm current room availability and rates with the guest house before relying on the displayed estimate.

