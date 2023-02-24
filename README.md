# BB DBMS
 CS 4433 Final Project

Introduction
For our project, we were tasked with implementing a detailed database for a real-world application. Our team chose to create a blood bank database in which users can set up a blood donation at a facility of their choice. The donation can then be used for patients in need of a blood transfusion. Our motivation to choose this topic was because now more than ever, the situation is dire as blood supply shortages impact millions across the nation during one of the worst worldwide pandemics in decades. The American Red Cross and local community blood centers are issuing a plea for all eligible donors to give. 

Our objective is to help individuals who are eager to donate have a platform to connect with professionals in an easy manner. Hence, we choose our project to be based on a blood bank database system. This database catalogs all the data for blood donations allowing the ease of access to information of healthcare facilities in an area. A distinctive feature of our application that sets us apart from other similar databases is that our application allows the donors to have limited relative information revealed about recipients who are in need. How unique and gratifying would it be to see your blood donation fight certain illnesses and save lives? 

The design of this database is to showcase the framework for all the data that comes in as well as to serve as a historical reference. The database shows all of the relevant information for the donations, the donors, recipients, facilities, and more, which will be explained in further detail later. 

Functionality of our Database

Basic functions include the ability for users (donors) to find relevant information about recipients by querying different illnesses to see who in the area needs blood. As security and privacy are crucial to us, the information that is revealed about the recipient would be limited to relevant information about the recipient including age, symptoms, blood type, and their location. The application also offers an interesting blood type compatibility search to see who you have the ability to help. For instance, if you type in your blood type as  B- the query will bring up all recipients who can receive B- blood, in this case it would be B-, AB-, and AB+. Users also have the ability to register with the database by inserting their personal information like name, age, sex, weight, health status, blood type, phone number and location. Root admin users have the ability to update and delete donors' personal information from the database. 
 
Our application's advanced function showcases Google's Map Platform by using a combination of Maps JavaScript API, the Places API and our own database. The Maps JavaScript API essentially pulls information from our database, specifically the locations table, which contains attributes of latitudes and longitudes of blood donation facilities. This allows the users to look up nearby geo locations on a map radius showing markers of places where they have the ability to donate. The map would also display information such as the name of the facility, the address and the contact information pertaining to the location.

Implementation of our Database

Our database design was extensive and consisted of the use of many helpful software and tools. We used USBWebServer v8.6.5, an all in one portable lightweight web server package (only for Windows), which comes included with Apache, PHP 8.1, MySQL and phpMyAdmin. 
The front end of the web interface and logic is implemented with the help of HTML and CSS. From there, we used PHP as the server-side scripting language to connect our front end to the backend blood bank database. To create and manage our database and the tables within, we used the free and open source phpMyAdmin tool to handle the administration of MySQL. 

Responsibilities

My responsibilities included implementing the basic functions like search, insert, update and delete as well as the advanced function. I also created the front and back end of the website application. Through my experience, I have learned how to create a database backed functioning web application. It was interesting to learn how to create CRUD operations for the basic functions of the system and realized just how important databases were and how foundational they had become to our system. This project allowed me to learn basic HTML/CSS, and object oriented programming using PHP and MySQL to create indexing and search systems. My programming skills have increased dramatically as a result of the database development as it was my first time learning and implementing Google’s APIs in a real world application. It was quite the challenge implementing the advanced function, but it was a good learning experience. Some of the other challenges I faced was the initial planning of the database itself and making sure the functional dependencies of the tables, and their attributes made sense for the app objective.

 
