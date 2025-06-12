Community Safety SA Application
This is a web application designed to empower communities in South Africa by providing a platform to report non-urgent safety incidents, access valuable safety resources, stay informed with local news and statistics, and manage personal incident reports.

✨ Features
Home (index.html): An inviting landing page providing an overview of the platform's purpose and key functionalities.

Report Incident (report-incident.html): A form for users to submit non-urgent incidents, including incident type, date, time, location (with optional live geolocation), and a detailed description.

Resources (resources.html): A section offering valuable safety tips, emergency contacts, and informative videos to help users enhance their personal safety.

News (news.html): Stay updated with the latest community safety news articles and view national crime statistics. This page also features personalized incident statistics based on your own reported data.

Login / Register (user-login.html): A basic user authentication system allowing users to log in or register. Successful login redirects to the homepage.

Admin (admin.html): (Placeholder/Under Development) A dedicated section for administrative functionalities.

🚀 How to Use
The application is designed to be straightforward for community members.

Navigate: Use the navigation bar at the top to move between different sections of the application.

Report an Incident:

Go to the "Report Incident" page.

Fill in the details about the incident. You can use the "Get Current Location" button to automatically populate latitude and longitude.

Click "Submit Report."

Important: Your reported incident data (type, date, time, location, etc.) is saved locally in your browser's storage (localStorage) and will be displayed on the "News" page under "Your Reported Incident Statistics." This data is specific to your browser and device and is not sent to a server for storage.

View Your Statistics:

Visit the "News" page.

Scroll down to the "Your Reported Incident Statistics" section to see charts visualizing the types and trends of incidents you've reported.

Access Resources: The "Resources" page provides useful information and videos for community safety.

🛠 Technologies Used
HTML5: Structure of the web pages.

CSS3: Styling and responsive design.

JavaScript: Core interactivity, form handling, and data management.

Chart.js: For rendering interactive data visualizations on the "News" page.

EmailJS: Integrated into the "Report Incident" form to send incident details via email (requires configuration with your EmailJS service ID and template ID).

Web Geolocation API: To capture the user's live location on the "Report Incident" form.

localStorage: Used for client-side storage of reported incident data for personalized statistics on the "News" page.

Firebase (Auth Only in user-login.html): The user-login.html page uses Firebase for user authentication (signing in and registering). Note that Firebase Firestore is NOT used for incident data storage as per current implementation.

⚙️ Running the Application
This is a client-side web application. You can open any of the HTML files (e.g., index.html, report-incident.html, news.html) directly in your web browser. There is no server-side setup required.

💡 Future Enhancements
Implementing server-side storage (e.g., Firebase Firestore, or a custom backend) for persistent and multi-device incident data.

Adding an admin interface for reviewing and managing reported incidents.

Implementing a search or filter function for news articles.

Expanding the resources section with more categories and content.

Integrating mapping services to display reported incidents visually (with privacy considerations).

Adding a feature for users to subscribe to news updates.
