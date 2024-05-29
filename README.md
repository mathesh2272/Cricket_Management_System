# Cricket Management System

A console-based project to manage cricket team and player information using a database.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contact Information](#contact-information)

## Description

Cricket Management System is a console-based application designed to manage cricket team details and player statistics. The system supports two types of users: Admin and User.

- **Admin**: Admins can log in to insert, update, and manage cricket team details, as well as player batting and bowling statistics.
- **User**: Users can log in to view team details, player details, and batting and bowling statistics for all players. Users can also search for a single player using their jersey number.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/CricketManagementSystem.git

2. Navigate to the project directory:

  ```sh
    cd CricketManagementSystem

3. Set up the database:
        Ensure MySQL is installed and running.
        Create a database named cricket_management and import the provided SQL script to set up the tables.
4. Install the necessary dependencies:
        Open the project in Eclipse.
        Ensure JDBC is properly configured in your project settings.

Usage

To run the application, execute the main class in Eclipse or use the command line:

  ```sh
  java -cp .;path\to\mysql-connector-java-x.x.xx.jar com.yourpackage.Main

Admin Login

    Enter the login type: Admin
    Enter the password.
    Once logged in, you can:
        Insert and update cricket team details.
        Insert and update player batting and bowling details.

User Login

    Enter the login type: User
    View options:
        View team details.
        View batting and bowling details for all players.
        Search for a player by their jersey number.

Features

    Admin functionalities:
        Insert and update cricket team details.
        Insert and update player statistics.
    User functionalities:
        View team and player details.
        Search for players by jersey number.

Contact Information

Connect with me on LinkedIn.
