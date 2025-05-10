README

Description:
This program has the ability to discover the floor plans of buildings in the western, display layers of washrooms, classrooms, and other points of interest, and allows users to insert, edit, and remove their own user favorite POI. 

Required libraries:
The library used in building the software is json-simple-1-1-1, which is used to save and load POI and Profile data in JSON formatted files. 
json-simple-1-1-1

Guide for building software:
1. Open the group41 project in Netbeans
2. Move on to Source Packages > com.cs2212.group41 > Group41
3. Run the file “Group41.java”
4. It should display the login page and you are free to use the program.
+  The json-simple-1-1-1 library is already included in the dependency and there is no need for an installment.

Guide to run software:
1. The software begins with a login page, enter username and password if you already have an account.
2. If you don’t have an account click on the “Create new account” button and it leads to the Registrations page.
2. 1 If you want to log in as a developer account, then use user1/password1
2. 2 If you want to log in as a regular account, then use user2/password2
3. Enter first name, last name, username, password, and confirm the password, and press “Register” to create a new account.
4. The program should lead you to the Login page. Login.
5. The program should open the Buildings page with a Western Campus map. Select a building you want to discover from the box under the “Available Building List”.
5. 1 The menu at the top right allows you to save and log out, save and close, display a help message, and display the current weather of the Western campus.
5. 2 The box above “Available Building List” allows you to search for a building.
6. Selecting a building from the Buildings page will lead you to the Floors page. You can scroll on a map on the right to see areas you want and read POI information.
7. To display/hide the layers, click the checkboxes from the drop-down menu at the top bar.
8. To change floors, select a floor from the drop-down menu above the floor plan map.
9. Click on the “Insert POI” button to insert a new POI
9. 1 Click on the map on the right to select the place where you want to insert a new POI.
9. 2 Enter the POI name, POI room number, POI Type, and Description in the boxes. Click on the “Insert” button. 
10. Select a POI to Edit and click on the “Edit POI” button to edit an already existing POI.
10. 1 To edit, enter the POI name, POI room number, POI Type, and Description in the boxes and click on the “Update” button. 
10. 2 To delete, select the POI to delete and click on the “delete” button.
11. To save your work, click “Save and Logout” or “Save and Close”.


User Guide:
This should be very similar to the steps in “Guide to run software”. Newly generated accounts from the Registration page are regular users. You can also use user2/password2 to run the program as a regular user. If you are using a regular account, you only get to insert, edit, and remove User created POIs.
How to access your editor mode:
The “guide to run software” is written based on the editor mode. To access as an editor, simply log in using an editor account user1/password1.


Helpful message:
Most of our POIs are built in the MC building. Please check on the MC building!
