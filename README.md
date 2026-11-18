# My_project_ADBMS
MongoDB Capstone Project

Student Information Management System

Project Overview

This project is based on MongoDB. It is designed to store and manage student information using a MongoDB database.

The project demonstrates basic database operations such as inserting, retrieving, searching, updating, deleting, sorting, filtering, and aggregation.

Student Information

* Student Name: Teena  Chaudhary
* Roll Number: 2601940036
* Technology: MongoDB
* Tools: MongoDB Compass and mongosh
* Database Name: CollegeDB
* Collection Name: Students

Technologies Used

* MongoDB
* MongoDB Compass
* MongoDB Shell (mongosh)
* JSON

Database Structure

The Students collection contains the following fields:

Field	Data Type
rollNo	Number
name	String
department	String
age	Number
marks	Number

Features

1. Create Database and Collection
2. Insert Student Records
3. Display All Student Records
4. Search Students by Name or Roll Number
5. Update Student Details
6. Delete Student Records
7. Filter Students by Department
8. Sort Student Records
9. Calculate Average Marks using Aggregation
10. Verify Final Database Records

Project Files

* students.json – Student records in JSON format.
* README.md – Project description and instructions.
* Capstone.pdf – Project documentation and screenshots.

How to Run the Project

Step 1: Open MongoDB Compass.

Step 2: Connect to your MongoDB server.

Step 3: Open the MongoDB Shell (mongosh).

Step 4: Select the database:

use CollegeDB

Step 5: Create the collection:

db.createCollection("Students")

Step 6: Import JSON data (if using a JSON file):

mongoimport --db CollegeDB --collection Students --file students.json --jsonArray

Step 7: Display student records:

db.Students.find()

Conclusion

This project helped me understand MongoDB database operations and how to manage student information using NoSQL databases. I successfully performed insertion, searching, updating, deletion, sorting, filtering, and aggregation operations.
