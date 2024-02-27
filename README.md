News Content Management System
Welcome to the News Content Management System! This system is designed to manage news content efficiently, allowing both administrators and content writers to contribute and manage articles seamlessly.

1.Features
.User Access Control: The system offers two main user roles: Admin and Content Writer. Admins have full control over the platform, while Content Writers can only post articles.
.CRUD Operations: Users can Create, Read, Update, and Delete news articles.
.Dynamic Website Settings: Admins can customize the website name, logo, and other settings to suit their preferences.
.Database Management: Utilizes a MySQL database with four main tables: posts, users, category, and settings.

2.Usage
.User Site
->Users can view news articles contributed by various content writers.
->Accessible features:
   .Browse articles
   .Search for articles
   .View article details
.Admin Site
->Admins have additional privileges to manage users, posts, and website settings.
->Accessible features:
   .Manage users: Create, view, edit, and delete user accounts.
   .Create and manage posts: Add, edit, and delete news articles.
   .Website settings: Customize website name, logo, and other configurations.
   
3.Setup
->Clone Repository: Clone this repository to your local machine.
->Database Configuration:
   .Import the SQL file (news-site.sql) into your MySQL database.
   .Configure database connection settings in config.php.
->Web Server Configuration:
   .Ensure your server is configured to run PHP files.(Generally prefer XAMPP)
   .Place the project files in your server directory.(place the fie in htdocs folder in xampp and the access it using localhost)
->Access:
   .Visit user.php to access the user site.
   .Visit admin.php to access the admin site.
   
4.Technologies Used
  ->PHP
  ->MySQL
  ->HTML
  ->CSS
  ->JavaScript
