# fullStack-quiz
IDE used for Project development:-
 1) Spring Tool Suits 4. For Backend development.
 2) Visual Studio Code.  For Frontend development.

Technology Used         Version
SpringBoot		2.1.7
MySQL			5.7.6
Angular                 8.2


For Spring Boot:

Step to run the project :-
 Step 1: Clone the project from git master branch into one Folder.
 
 Step 2: Import the your cloned project into the sts. For Import the project follow the below given steps.
         Open Spring Tool Suits.
         Go to the File =>Import=>Maven>Existing Maven Project and then browse your Project
		 
 Step 3: Then Update the imported project. For Update follow the below given steps.
         Right Click on the Project.
		 Then Go to Maven => Update Project => Checked "Force Update of Snapshots/Release"  and click Ok.
		 
 Step 4: Open application.properties file inside the "/todos-application/src/main/resources/application.properties" and update your  database "username" and "password".
 
 Step 5: Create Database with name "todosapplication" in your MySQL.
 
 Step 6: Now we are ready to run our project. For Run follow the below given steps.
         Go to the class "/todos-application/src/main/java/com/todos/TodosApplication.java" And right click on the TodosApplication.java
		 Go to Run As => Spring Boot App and click.

For Angular:

Step to run the project :-
  Step 1: Clone the project from git master branch into one Folder.

  Step 2: Import the your cloned project into the VSCode. For Import the project follow the below given steps.
	  Open VSCode
	  Go to the File =>Open Folder=> and then browse your Project
  
  Step 3: Open Terminal and run the command "npm install" to download to the dependencies.

  Step 4: To run the project use command "ng serve --open"

