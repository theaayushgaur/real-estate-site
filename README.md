#table overview-

+-----------------------+
| Tables_in_sql_project |
+-----------------------+
| Customer              |
| Property              |
| Sold_Property         |
| agent                 |
+-----------------------+

 Customer Metadata-
+-------------+-------------+------+-----+---------+-------+
| Field       | Type        | Null | Key | Default | Extra |
+-------------+-------------+------+-----+---------+-------+
| C_Id        | int         | NO   | PRI | NULL    |       |
| C_Mobile_No | bigint      | YES  |     | NULL    |       |
| C_Email_Id  | varchar(80) | YES  |     | NULL    |       |
| C_Name      | varchar(40) | YES  |     | NULL    |       |
| C_Password  | varchar(40) | YES  |     | NULL    |       |
+-------------+-------------+------+-----+---------+-------+


Property Metadata-
+-------------+--------------+------+-----+---------+-------+
| Field       | Type         | Null | Key | Default | Extra |
+-------------+--------------+------+-----+---------+-------+
| PropertyId  | int          | NO   | PRI | NULL    |       |
| City        | varchar(50)  | YES  |     | NULL    |       |
| Street_Name | varchar(40)  | YES  |     | NULL    |       |
| House_Name  | varchar(40)  | YES  |     | NULL    |       |
| Pincode     | varchar(12)  | YES  |     | NULL    |       |
| size        | int          | YES  |     | NULL    |       |
| floor       | int          | YES  |     | NULL    |       |
| A_id        | int          | YES  |     | NULL    |       |
| C_id        | int          | YES  |     | NULL    |       |
| IsSold      | varchar(20)  | YES  |     | NULL    |       |
| IsRent      | varchar(20)  | YES  |     | NULL    |       |
| image_link  | varchar(100) | YES  |     | NULL    |       |
| Description | text         | YES  |     | NULL    |       |
| Listed_Date | date         | YES  |     | NULL    |       |
| Sold_Date   | date         | YES  |     | NULL    |       |
| no_of_rooms | int          | YES  |     | NULL    |       |
| Cost        | int          | YES  |     | NULL    |       |
+-------------+--------------+------+-----+---------+-------+


Property Metadata-
+-------------+--------------+------+-----+---------+-------+
| Field       | Type         | Null | Key | Default | Extra |
+-------------+--------------+------+-----+---------+-------+
| PropertyId  | int          | NO   | PRI | NULL    |       |
| City        | varchar(50)  | YES  |     | NULL    |       |
| Street_Name | varchar(40)  | YES  |     | NULL    |       |
| House_Name  | varchar(40)  | YES  |     | NULL    |       |
| Pincode     | varchar(12)  | YES  |     | NULL    |       |
| size        | int          | YES  |     | NULL    |       |
| floor       | int          | YES  |     | NULL    |       |
| A_id        | int          | YES  |     | NULL    |       |
| C_id        | int          | YES  |     | NULL    |       |
| IsSold      | varchar(20)  | YES  |     | NULL    |       |
| IsRent      | varchar(20)  | YES  |     | NULL    |       |
| image_link  | varchar(100) | YES  |     | NULL    |       |
| Description | text         | YES  |     | NULL    |       |
| Listed_Date | date         | YES  |     | NULL    |       |
| Sold_Date   | date         | YES  |     | NULL    |       |
| no_of_rooms | int          | YES  |     | NULL    |       |
| Cost        | int          | YES  |     | NULL    |       |
+-------------+--------------+------+-----+---------+-------+

agent Metadata-
+---------------+--------------+------+-----+---------+-------+
| Field         | Type         | Null | Key | Default | Extra |
+---------------+--------------+------+-----+---------+-------+
| A_Name        | varchar(40)  | YES  |     | NULL    |       |
| A_Id          | int          | NO   | PRI | NULL    |       |
| A_Email_Id    | varchar(60)  | YES  |     | NULL    |       |
| A_Password    | varchar(100) | YES  |     | NULL    |       |
| A_MobileNo    | bigint       | YES  |     | NULL    |       |
| Total_Sales   | bigint       | YES  |     | NULL    |       |
| profile_photo | varchar(100) | YES  |     | NULL    |       |
+---------------+--------------+------+-----+---------+-------+




# real-estate-site
This is a real estate buying,selling and renting site, which is the final project for the DBMS course.
It has two interfaces,one for agent side and one for client side.Both have their own functionality.
# In Agent side -
One can register themself as an agent for the website and upload the property which they have and
they can keep track of what are sold and what are listed and can check how much they have earned and to whom 
they have sold their properties to.
# In Client Side-
A client is the one who is looking for property so he can search based on few parameters like country,state,
city,no. of rooms and location and based on these results and most liked property we present them the search

This project is being jointly done by Soumyajit Deb and Yash Kothari

Soumyajit Deb (Roll no: 1801176)  

Yash Kothari  (Roll No: 1801200)
