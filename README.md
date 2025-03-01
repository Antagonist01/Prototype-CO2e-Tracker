Prototype-CO2e-Tracker
This repository contains the front-end code for the Quantum Sustainability Carbon Emissions Tracker. The application is designed to track and manage carbon emission data across multiple scopes (Scope 1, Scope 2, and Scope 3) with a modern, futuristic interface.

Overview
The project is built using pure HTML, CSS, and JavaScript. It provides a static front-end that includes:

Login and Unit Selection:
A dedicated login page that simulates user authentication using email and password, with a unit selection dropdown displayed in a footer area.

Multi-Scope Data Entry Forms:
Separate pages for each emission scope (Scope 1, Scope 2, and Scope 3) that allow users to enter data for fuel, electricity/utility, and other emission sources.

#Note: In Scope 1, the unit is already selected on the login page, so it isn't repeated.
#Real-Time File Upload Timestamp:
#When a file is selected in the form, the application displays its last modified time in real time.

Responsive and Futuristic Design:
A sleek, responsive design with shared CSS styling ensures a consistent and professional look across the application.

File Structure
Prototype-CO2e-Tracker/
├── login.html          # Login page with unit selection
├── scope1.html         # Emission data entry form for Scope 1 (Fuel Data)
├── scope2.html         # Emission data entry form for Scope 2 (Electricity/Utility Data)
├── scope3.html         # Emission data entry form for Scope 3 (Other Emissions)
└── style.css           # Shared CSS styling for all pages
Getting Started
To run this project locally:

Clone the repository:

git clone https://github.com/Antagonist01/Prototype-CO2e-Tracker.git
Navigate to the project directory:

cd Prototype-CO2e-Tracker
Open the HTML files in your browser: For example, open login.html to start the application.

Future Enhancements
Backend Integration: Connect the front-end to a Python-based RESTful API and a MySQL database for dynamic data storage and retrieval.

Enhanced Authentication: Implement secure authentication with proper user session management.

Desktop Packaging: Package the application as an executable (.exe) for local, offline use by selected users.

License
This project is licensed under the MIT License. See the LICENSE file for details.

- **Desktop Packaging:**
  Package the application as an executable (.exe) for local, offline use by selected users.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
