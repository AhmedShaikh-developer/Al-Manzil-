Al-Manzil Real Estate Website

Description

Al-Manzil is a real estate website built using PHP that enables users to list and sell their properties. It features two panels: one for users to manage their property listings and another for the admin to oversee the platform and its users.

How to Run Locally
To run this project on your localhost, follow these steps:

1. Clone the Repository
   
git clone https://github.com/your-username/al-manzil.git

2. Set Up the Database
   
Create a MySQL database and import the included SQL file (database.sql) to set up the required tables.

Configure the Database Connection

3. Navigate to the config directory and open db.php.
   
Modify the database connection parameters (hostname, username, password, database name) to match your local environment.

5. Start a Local Server
   
You can use tools like XAMPP or WAMP to run a local server. Alternatively, you can use PHP's built-in server:
php -S localhost:8000

7. Access the Website
   
Open your web browser and go to http://localhost:8000.


User Panel

Users can register, log in, and manage their property listings.

They can add details about their properties, including title, description, location, and price.

Users can also edit or delete their listings.


Admin Panel

The admin panel provides an overview of all users and their respective properties.

The admin can view, edit, or delete user accounts and property listings.


Dependencies

PHP (7.0+)

MySQL

Web server (Apache, Nginx, or PHP's built-in server)


Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request with a detailed description of your changes.
