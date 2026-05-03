▶️ How to Run the Project (PHP)

Install a local server like XAMPP (or WAMP)

Extract the ZIP file into the htdocs folder

Example path:

C:\xampp\htdocs\your-project-folder

Start Apache and MySQL from XAMPP Control Panel

Import the database:

Open browser → http://localhost/phpmyadmin

Create a new database

Click Import → select .sql file from project → Import

Run the project in browser:

http://localhost/your-project-folder

⚠️ Notes

Make sure database name in your PHP file matches your created database

Update db.php (or config file) if needed:

$conn = mysqli_connect("localhost", "root", "", "your_database_name");
