Event Finder Website
Overview
Event Finder is a single-page, responsive website built to showcase events with a clean and modern user interface. The website consists of three pages: Home, Events, and Contact. The Home page features a hero section and a selection of featured events, the Events page lists all events with search functionality, and the Contact page includes a non-functional contact form. The project uses HTML5, CSS3 with Bootstrap, and Vanilla JavaScript to meet the requirements of a responsive, user-friendly event discovery platform.
Features

Navigation Bar: A responsive top navigation bar with links to Home, Events, and Contact pages, including a placeholder logo.
Home Page:
Hero section with the heading "Discover Events Near You."
Featured Events section displaying 4 sample events with a search bar to filter by event name.


Events Page:
Lists all events with the same search functionality as the Home page.
Displays event cards with name, date, time, location, description, and a non-functional "Register" button.


Contact Page:
Includes a non-functional contact form with fields for name, email, and message.


Design:
Uses Bootstrap 5.3.3 for responsive layout and styling.
Custom CSS for a gradient hero section, card hover effects, and mobile-friendly adjustments.


Bonus Features:
Search bar on Home and Events pages to filter events by name in real-time.
Dynamic event loading using dummy JSON data, simulating a data fetch with JavaScript.



Tech Stack

HTML5: For page structure.
CSS3: Custom styles with Bootstrap 5.3.3 for responsive design.
JavaScript: Vanilla JavaScript for dynamic event rendering and search functionality.

Project Structure
event-finder/
├── index.html        # Home page with hero and featured events
├── events.html       # Events page listing all events
├── contact.html      # Contact page with a contact form
└── README.md         # Project documentation

Setup Instructions

Clone or Download the Project:
Download the project files (index.html, events.html, contact.html, and README.md) to a local directory.


Host the Files:
No server is required for basic functionality, as the website uses static HTML, CSS, and JavaScript.
Place all HTML files in the same directory to ensure navigation links work correctly.


Open in a Browser:
Open index.html in a modern web browser (e.g., Chrome, Firefox, Edge) to view the Home page.
Use the navigation bar to access the Events and Contact pages.


Dependencies:
The website uses Bootstrap 5.3.3, loaded via CDN, so an internet connection is required to fetch Bootstrap CSS and JS.
No additional dependencies or build steps are needed.



Usage

Home Page:
View the hero section and browse featured events.
Use the search bar to filter events by name (e.g., type "Tech" to filter for "Tech Conference 2025").


Events Page:
Browse all events with the same search functionality.
Event cards display name, formatted date and time, location, description, and a "Register" button (non-functional).


Contact Page:
View the contact form with fields for name, email, and message (non-functional, styled for display only).


Navigation:
Click the logo or navigation links to switch between pages.
The active page is highlighted in the navigation bar.



Notes

Responsiveness: The website is fully responsive, tested for mobile, tablet, and desktop devices using Bootstrap's grid system and custom media queries.
Event Data: Events are loaded from a dummy JSON array in JavaScript, simulating a data fetch. No backend is implemented.
Form: The contact form is styled but non-functional, as no backend processing is required per the task.
Testing: Ensure all HTML files are in the same directory to avoid broken navigation links. Open the files directly in a browser or use a local server (e.g., python -m http.server).

Future Improvements

Add a backend to handle form submissions and store event data.
Implement actual event registration functionality.
Add pagination or infinite scroll for larger event lists.
Include event images in cards for enhanced visuals.

License
This project is for demonstration purposes and not licensed for commercial use. All content uses placeholder data and assets.
