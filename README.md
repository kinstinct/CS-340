# CS-340
About the Project/Project Title
The purpose of the "Animal Shelter" app is to give the user statistical knowledge. MongoDB and Python are used to create a fully functional web application that makes it possible to explore the Animal Shelter Data.

Motivation
This application was carefully designed to assess my proficiency in database administration and efficient data manipulation. This was done by using sophisticated methods and experimenting with different data architectures.

Part I

Getting Started
To begin, the application, 

-	Open Mongo, then import the aac_shelter_outvome.csv file.
 
-	The user would then want to create both a simple and a complicated index in order to parse the data contained in the page.
 
 
-	To authenticate and access the database, a user would now need to create both an admin account and an aacuser account.
 
 
-	The user would then need to install or have access to Python in order to run the program from a notebook.
List the tools you need to use the software and how to install them.
-	To utilize this software, a user needs MongoDB to access the database and a current version of Python to run the.py and.ipynb files.

Usage
Code Example

A Create method was created to insert a document into the AnimalShelter MongoDB database and collection. A user can also generate new animals in a shelter using the provided code. If an animal is successfully added, a confirmation message will appear, indicating that no mistakes occurred and that the creation was successful.
-	Input -> argument to function should be the key/value lookup pair to use with the MongoDB driver find API call.
-	Return -> “True” if successful insert, else “False”.
 
A Read method was created that queries for document(s) from the AnimalShelter MongoDB database and specified collection. The CRUD processes allow a user to read or search the current database for information about certain animals.
Input -> arguments to function should be the key/value lookup pair to use with the MongoDB driver find API call.
Return -> result in a list if the command is successful, else an empty list.
 An Update method was created that queries for and changes document(s) from the AnimalShelter MongoDB database and specified collection. The update method allows a user to change any information in the database.
Input -> arguments to function should be the key/value lookup pair to use with the MongoDB driver Find API call. The last argument to function will be a set of key/value pairs in the data type acceptable to the MongoDB driver update_one() or update_many() API call.
Return -> The number of objects modified in the collection.
 A Delete method was created that queries for and removes document(s) from the AnimalShelter MongoDB database and specified collection. The delete method removes information selected by the user to remove from the database.
Input -> arguments to function should be the key/value lookup pair to use with the MongoDB driver find API call.
Return -> The number of objects removed from the collection.
 

Tests
In order to run the tests in Jupiter Notebook, the MongoCRUD AnimalShelter database was imported and an instance for the AnimalShelter was created:
 
 
A Python script was created that imports a CRUD Python module to call and test all instances of CRUD functionality.

Screenshots
	Test the create method
 
	Test read method
 
	Testing the read method if null
 
	Creating data to test the update method
 
	Testing the update method

 
	Testing the delete method

 












Part II

The front-end development of the web application was the main emphasis of this project. For the stakeholders, we had to design an interactive dashboard that enabled them to navigate the Shelter Data and Geolocation capabilities on a map widget. A supplemental visual that provides insight into the distribution of filtered breeds was also required of us. Water rescue, mountain rescue, and disaster rescue were the three distinct rescue functions. The requirements for adoption into the program varied depending on the breed, sex, and age of each of these distinct rescue types.


                 
Beginning page/Reset Selection 
Water Rescue Selection 
Mountain & Disaster Rescue Selection 
Disaster or Individual Tracking Selection 

Contact
Your name: Patrick Cochran
