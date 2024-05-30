Assume i'm hired by ACME Corp. as a programmer.  The company wants me to finish developing their Student Directory web application where users should be able to: 
1. Create/add a new student
2. Read/view a list of students
3. Update/edit an existing student
4. Delete/remove an existing student

The main page of the web application is shown below.  The main page shows the list of students already on the database. 
![image](https://github.com/seifeldin123/DataBank-JSF-JDBC-Student-/assets/133134492/64042e43-f085-454e-adac-5e3b8c616dfe)


Clicking the “Add New Student” button on the main page should redirect the user to the Add New Student page shown below: 

![image](https://github.com/seifeldin123/DataBank-JSF-JDBC-Student-/assets/133134492/b50a5cd7-16ae-45c6-bf71-cf6ad4d4f8b7)

Clicking the “Add New Student” button (after entering all the necessary information), should insert the new student to the database and redirect the user back to the main page. 
Clicking the “Back” button above should simply cancel the add operation and redirect the user back to the main page. 
Clicking the “Edit” button on the main page should redirect the user to the “Update Student” page shown below: 

![image](https://github.com/seifeldin123/DataBank-JSF-JDBC-Student-/assets/133134492/4a31cf44-ead9-4a17-8cd2-06694a0a8d14)

Clicking the “Edit” button (after updating all the necessary information), should update the existing student on the database and redirect the user back to the main page.  
Clicking the “Back” button above should simply cancel the update operation and redirect the user back to the main page. 
Clicking the “Delete” button on the main page should trigger a pop-up to confirm if the user wants to proceed with deleting the selected student. 
Clicking OK on the pop-up should remove the selected student from the database as well as from the list of students shown on the main page.  
Clicking the “Cancel” button should simply cancel the delete operation. 
![image](https://github.com/seifeldin123/DataBank-JSF-JDBC-Student-/assets/133134492/cfb72938-26da-4e20-a76a-2af73b0cef84)

Finally, the company wants you to display your student information on the main page (below the table) so that they would know who to contact if something goes wrong while using the web application. 

After completing this project, i will be achievig: 
1. Create a model class to represent a database row
2. Create a managed bean class to manipulate the model class
3. Create a DAO class to manipulate the database
4. Create a JSF application that supports Create – Read – Update – Delete lifecycle for instances of the model class 
