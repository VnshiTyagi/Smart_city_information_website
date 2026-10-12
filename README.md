# Smart City Information Portal

A simple, responsive website that provides information about smart city initiatives, public services, transportation and sustainable urban development. Built with plain HTML, CSS and a little JavaScript.

## Features

- **Welcome section** with an overview of what a smart city is
- **Smart City Initiatives:** command centre, smart street lighting, public Wi-Fi, smart infrastructure
- **Public Services:** table of online bill payment, healthcare, education and waste tracking
- **Smart Transportation:** public transit, traffic management and electric mobility
- **Sustainable Urban Development:** solar power, waste management, water recycling, green spaces, plus a 4-phase roadmap
- **Citizen Feedback form** that shows a confirmation message with the entered name, email and topic
- **Responsive design:** works on laptops, tablets and phones

## Project Structure

```
smart-city/
├── index.html    # Page structure and content (and form script)
├── style.css     # Styling and responsive layout
└── README.md     # Project documentation
```

## How to Run

1. Download or clone the project folder.
2. Keep `index.html` and `style.css` in the same folder.
3. Open `index.html` in any web browser.

No installation or server is required.

## How the Feedback Form Works

When the form is submitted, JavaScript stops the page from reloading, reads the name, email and topic, and displays a "Registration Successful" message below the form. The data is only shown on the page. It is **not** stored or sent anywhere.

## Responsiveness

- The viewport meta tag makes mobile browsers use the real screen width.
- Media queries adjust spacing and text size for tablets (up to 800px) and phones (up to 600px).
- On phones, the table is shown as stacked cards and the Submit button becomes full width.

## Technologies Used

- HTML5
- CSS3 (media queries)
- JavaScript (form handling)

## Possible Improvements

- Add images and icons for each section
- Store feedback using a backend or database
- Add form validation messages
- Add a dark mode option

## Author

Made as a first-year college project.

## License

This project is for educational purposes.
