Project Overview
The project is a simple PHP-based web application designed to read and process CSV files containing transaction data. The main goals of the project are to read transaction data from multiple CSV files, process this data to calculate various financial metrics (such as total income, total expense, and net total), and display this data in a formatted HTML table.

Here’s a detailed breakdown of the project setup and functionality based on the instructions provided:

1. Project Structure and Setup
Document Root: The document root should be set to YOUR_PROJECT/public. This means that the web server should point to the public directory, and all requests will be handled from there.

Main File (index.php): The public/index.php file serves as the entry point of the application. It is responsible for including or requiring all other necessary files to make the application function.

Constants:

APP_PATH: Typically points to the app directory where your main application logic is stored.
FILES_PATH: Points to the directory where the transaction CSV files are stored (transaction_files).
VIEWS_PATH: Points to the directory where the HTML view templates are stored (views).
2. Application Logic (app Directory)
Main Logic File (App.php): The app/App.php
