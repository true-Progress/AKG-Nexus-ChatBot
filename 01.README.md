# AKG-Nexus-ChatBot
The AKGEC Smart Chatbot is a web-based assistant built with HTML, CSS, and JavaScript that helps students access college information quickly. It answers queries, shows campus locations via Google Maps, supports dark mode, and includes a simulated login, making it a simple and efficient student help tool.


🔧 How the Chatbot is Built & Technologies Used
>HTML (Structure)
Creates chatbot layout, chat window, input box, buttons, and login modal
Defines the overall structure of the web application

>CSS (Design & UI)
Used for styling with Glassmorphism UI (blur, transparency, shadows)
Implements dark mode using CSS variables
Ensures responsive design for mobile and desktop

>JavaScript (Core Logic)
Handles user input and chatbot responses
Uses keyword matching + basic NLP for answering queries
Dynamically updates chat messages in real-time

>Google Maps Integration
Embedded using <iframe>
Allows users to view and navigate the campus interactively

>Login System (Frontend Only)
Popup modal created using HTML + JS
Simulates login using local storage (no backend)

>Data Handling
Predefined knowledge base stored in JavaScript
Uses Fetch API to try retrieving notices/news from college website

>Deployment
Fully frontend-based → can run directly in browser
Easily deployable on GitHub Pages / Netlify
