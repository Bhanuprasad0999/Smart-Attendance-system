📚 Smart Attendance System
A streamlined web application designed to automate the process of taking attendance using facial identification. This project focuses on a clean user interface and seamless integration between front-end capture and back-end data storage.

🚀 Features
User Registration: Capture and register student faces linked to specific Roll Numbers.

Real-time Attendance: Uses the browser's webcam to capture images and match them against the database.

Admin Dashboard: A secure area for administrators to view attendance logs in a tabular format.

Data Export: Capability to export attendance records into Excel (.csv) for official reporting.

Responsive UI: Built with HTML5 and CSS3 for a smooth user experience across devices.

🛠️ My Role & Contributions
As the Front-End Developer, I was responsible for:

UI/UX Design: Designing the layouts for index.html, attendance.html, and register.html using CSS to ensure a professional and intuitive look.

Webcam Integration: Implementing the MediaDevices API to access the user's camera directly within the browser.

Data Binding: Connecting the HTML forms and JavaScript fetch requests to the PHP back-end to ensure data (images and roll numbers) is sent correctly to the server.

Dynamic Tables: Creating the admin dashboard views that pull data from the server and display it in a clean, readable format.

💻 Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6)

Backend: PHP (Server-side logic and file handling)

Storage: CSV-based data logging (Scalable to SQL)

Tools: XAMPP/Apache Server

📂 Project Structure
index.html - The main landing page/navigation hub.

register.html - Interface for capturing new student faces.

attendance.html - Interface for marking daily attendance.

admin_dashboard.php - Backend-driven page to display recorded attendance.

save_face.php & match_face.php - PHP scripts handling the image processing and logic.
