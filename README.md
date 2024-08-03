# SEMS

## Introduction

This application helps in managing student information and sends email notifications to students for initial passwords and updates.

## Getting Started

To get started with this application, follow the steps below:

### Prerequisites

Make sure you have the following installed:
- PHP
- A web server (e.g., Apache)
- MySQL

### Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/hekuranTEST/SEMS.git


2. **Migration and Seedings**
    ```sh
    acess the route http://localhost/server/config/migration/migration.php to migrate the database and seed with default data.

Usage
    Authenthication
        Once a seeding is executed then you can logIn or logOut as a profesor or Student, it has protected routes in front-end and in back-end.
    Functionality
        Profesor:
            Once a professor logs in, they can create, update, or delete students. The system automatically sends an email to the student with a default password and an opportunity to change the password (not yet implemented).
        Student:
            Student once logIn successfully it can update their personal data.


Additional Notes
Ensure that your web server is running and configured to serve the application.
Make sure that your email server settings allow sending emails from the configured email address.
Contributing
If you wish to contribute, please fork the repository and create a pull request.



    

