<!DOCTYPE html>
<html>
<head></head>
<body>

<h1>Cricket Management System</h1>

<p>A console-based project to manage cricket team and player information using a database.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#description">Description</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#contact-information">Contact Information</a></li>
</ul>

<h2 id="description">Description</h2>
<p>Cricket Management System is a console-based application designed to manage cricket team details and player statistics. The system supports two types of users: Admin and User.</p>
<ul>
    <li><strong>Admin</strong>: Admins can log in to insert, update, and manage cricket team details, as well as player batting and bowling statistics.</li>
    <li><strong>User</strong>: Users can log in to view team details, player details, and batting and bowling statistics for all players. Users can also search for a single player using their jersey number.</li>
</ul>

<h2 id="installation">Installation</h2>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/mathesh2272/CricketManagementSystem.git</code></pre>
    </li>
    <li>Navigate to the project directory:
        <pre><code>cd CricketManagementSystem</code></pre>
    </li>
    <li>Set up the database:
        <ul>
            <li>Ensure MySQL is installed and running.</li>
            <li>Create a database named <code>cricket_management</code> and also create the necessary tables for the database.</li>
        </ul>
    </li>
    <li>Install the necessary dependencies:
        <ul>
            <li>Open the project in Eclipse.</li>
            <li>Ensure JDBC is properly configured in your project settings.</li>
        </ul>
    </li>
</ol>

<h2 id="usage">Usage</h2>
<p>To run the application, execute the main class in Eclipse or use the command line:</p>
<pre><code>java -cp .;path\to\mysql-connector-java-x.x.xx.jar com.yourpackage.Main</code></pre>

<h3>Admin Login</h3>
<ul>
    <li>Enter the login type: <code>Admin</code></li>
    <li>Enter the password.</li>
    <li>Once logged in, you can:
        <ul>
            <li>Insert and update cricket team details.</li>
            <li>Insert and update player batting and bowling details.</li>
        </ul>
    </li>
</ul>

<h3>User Login</h3>
<ul>
    <li>Enter the login type: <code>User</code></li>
    <li>View options:
        <ul>
            <li>View team details.</li>
            <li>View batting and bowling details for all players.</li>
            <li>Search for a player by their jersey number.</li>
        </ul>
    </li>
</ul>

<h2 id="features">Features</h2>
<ul>
    <li>Admin functionalities:
        <ul>
            <li>Insert and update cricket team details.</li>
            <li>Insert and update player statistics.</li>
        </ul>
    </li>
    <li>User functionalities:
        <ul>
            <li>View team and player details.</li>
            <li>Search for players by jersey number.</li>
        </ul>
    </li>
</ul>

<h2 id="contact-information">Contact Information</h2>
<p>If you have any questions or suggestions, feel free to reach out to me.</p>
<p>Connect with me on <a href="https://linkedin.com/in/matheshm">LinkedIn</a>.</p>

</body>
</html>

