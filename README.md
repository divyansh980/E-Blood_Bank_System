E-Blood Bank Management System
Overview
The E-Blood Bank Management System is a web-based application designed to streamline the process of blood donation and management. It connects donors and recipients, making it easier to manage blood donations, requests, and related information efficiently.
Features
User Registration and Login: Users can sign up and log in to access the system.
Donor Management: Add, update, and manage donor information.
Blood Requests: Manage blood requests from recipients.
Admin Dashboard: Admins can manage blood groups, donors, and requests.
Profile Management: Users can update their profiles.
Search Donors: Search for donors based on blood group and location.
Contact Us: Users can contact the blood bank for queries.
Project Structure
   .
├── about.php
├── admin/
│   ├── add-bloodgroup.php
│   ├── add-donor.php
│   ├── blood-requests.php
│   ├── change-password.php
│   ├── css/
│   ├── dashboard.php
│   ├── donor-list.php
│   ├── download-records.php
│   ├── fonts/
│   ├── forgot-password.php
│   ├── img/
│   ├── includes/
│   ├── index.php
│   ├── js/
│   ├── logout.php
│   ├── manage-bloodgroup.php
│   ├── manage-conactusquery.php
│   └── ...
├── change-password.php
├── contact-blood.php
├── contact.php
├── css/
├── donor-list.php
├── images/
├── includes/
├── index.php
├── js/
├── login.php
├── logout.php
├── profile.php
├── request-received.php
├── saerch-donar.php
├── search-donor.php
├── sign-up.php
└── webfonts/
Installation
  Clone the repository:
      git clone https://github.com/yourusername/e-blood-bank.git
  Navigate to the project directory:
    cd e-blood-bank
Set up the database:
  Import the SQL file located in the database directory into your MySQL database.
  
Configure the database connection:
  Update the database configuration in config.php.
Usage
Start the web server:
  php -S localhost:8000
Open your web browser and navigate to http://localhost:8000.
Contributing
  Fork the repository.
  Create a new branch:
    git checkout -b feature-branch
    
Make your changes and commit them:
  git commit -m "Description of changes"
Push to the branch:
  git push origin feature-branch
Open a pull request.
License
  This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgements
  Bootstrap
  jQuery
  DataTables
  FontAwesome
