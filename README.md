Name: G.GIRISH
Company: CODTECH IT SOLUTIONS
ID: CT08DTQ
Domain: Full Stack Web CTDevelopment
Duration: Dec, 2024 to Jan, 2025
Mentor: Sravani Gouni

Overview of the project

Project: PERSONAL PORTFOLIO WEBSITE WITH BACKEND

Objective:

Create a personal portfolio website with a backend to manage content. This
project helps you learn HTML, CSS, JavaScript, and a backend framework like
Express.js or Flask. Design a responsive frontend using HTML, CSS, and
JavaScript. Create a backend to manage projects and blog posts.

Personal Portfolio Website with Content Management:

This project is a personal portfolio website that includes a backend for managing content such as projects and blog posts. It allows users to view a list of projects and blog posts dynamically, with the content being served by a Node.js Express backend. This project aims to showcase the development skills in full-stack web development, including frontend design, backend development, and API management.

Features:

Responsive Design: The website is mobile-friendly and adjusts its layout for different screen sizes.
Dynamic Content: Project and blog post data are fetched from the backend via API calls.
Content Management: The backend allows easy management of project and blog post content stored in JSON files.
Navigation: Simple navigation between the Projects and Blog sections of the site.
Backend API: An Express.js backend to serve content (projects and blog posts) through API endpoints.
Technologies Used
Frontend:
HTML
CSS (Grid Layout, Flexbox, Responsive Design)
JavaScript (for DOM manipulation and data fetching)
Backend:
Node.js
Express.js
Data Management:
JSON files for storing and serving project and blog post data.
Getting Started
Prerequisites
Before you begin, ensure you have the following installed:

Node.js (includes npm)
A code editor such as VS Code
Installing and Running the Project Locally
Clone the Repository: First, clone the repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/personal-portfolio.git
Navigate to the Project Directory:

bash
Copy code
cd personal-portfolio
Install Dependencies:

Install the required dependencies for the backend:

bash
Copy code
npm install
Run the Application:

Start the backend server:

bash
Copy code
node backend/server.js
The server will be running at http://localhost:3000. You can now access the portfolio website in your browser.

Folder Structure
plaintext
Copy code
personal-portfolio/
│
├── backend/
│   ├── server.js           # Express server
│   └── data/               # Project and blog data in JSON files
│       ├── projects.json   # Mock project data
│       └── blogPosts.json  # Mock blog post data
│
├── frontend/
│   ├── index.html          # HTML structure of the portfolio
│   ├── styles.css          # Styling for the website
│   └── scripts.js          # JavaScript to fetch and display dynamic content
│
└── package.json            # Node.js dependencies and scripts
API Endpoints
The following API endpoints are available for fetching content:

GET /api/projects – Returns a list of projects in JSON format.
GET /api/blogPosts – Returns a list of blog posts in JSON format.
How to Contribute
Feel free to fork this repository, make changes, and submit pull requests. If you encounter any issues or have suggestions for improvement, open an issue on GitHub.

License
This project is open-source and available under the MIT License.

Additional Information
This project was created to:

Practice full-stack development: Integrating a frontend with a backend and understanding how APIs work.
Showcase my web development skills: Including HTML, CSS, JavaScript, and Node.js.
Learn Express.js: Handling routing, serving static files, and building a RESTful API.
Demo
You can view the live demo of the portfolio here (if deployed).

Notes
The backend is intentionally simplified and uses JSON files for data storage. In a production environment, this could be replaced with a database (e.g., MongoDB, PostgreSQL).
The frontend is built to be responsive and works on both desktop and mobile devices.
The API serves static data but could be extended to support CRUD operations (Create, Read, Update, Delete) if you decide to implement a database.
