Aura Events
A front-end-only website for planning virtual events, built with HTML, CSS, and JavaScript. The project is designed for a student team of 6 members, featuring 6 interactive pages.
Features

Home: Hero section with a countdown timer and Swiper slider.
About: Mission statement and profiles for the 6-member team.
Services: Interactive service cards for event planning tools.
Budget Calculator: Real-time expense calculator with LocalStorage.
Guest List: Add/remove guests with LocalStorage persistence.
Contact: Form with client-side validation.

Tech Stack

HTML/CSS: Responsive design with Flexbox and Grid.
JavaScript: Interactivity with DOM manipulation and LocalStorage.
Libraries:
Swiper (v9) for sliders.
Font Awesome (v6.2.1) for icons.


No backend: All data is stored in LocalStorage.

Project Structure
├── home.html
├── about.html
├── services.html
├── budget.html
├── guests.html
├── contact.html
├── styles.css
├── app.js
├── images/
│   ├── home1.jpg
│   ├── home2.jpg
│   ├── home3.jpg
│   ├── about.jpg
│   ├── team1.jpg
│   ├── team2.jpg
│   ├── team3.jpg
│   ├── team4.jpg
│   ├── team5.jpg
│   ├── team6.jpg
└── README.md

Setup

Clone the repository.
Ensure the images/ folder contains the required images (or update paths).
Open home.html in a browser or serve the project using a local server (e.g., npx serve).
Test responsiveness using browser DevTools.

Running with Node.js
To test app.js with Node.js (v18.19.1):
node app.js

Note: app.js is designed for browser execution, so use a tool like live-server for full functionality:
npm install -g live-server
live-server

Team Roles

Mohammad Hussain: Home + Contact (timer, form validation).
Alekhya: About (team cards).
Hema Sagar: Services (service cards).
Satya Moulika: Budget Calculator (calculations, LocalStorage).
Guru Sai: Guest List (table management, LocalStorage).
Sai Deepika: CSS animations and responsiveness.

Notes

Replace placeholder images in the images/ folder.
Ensure internet access for CDN-hosted Swiper and Font Awesome.
Test LocalStorage functionality across pages.
For further customization (e.g., specific event types), edit content in HTML files.

