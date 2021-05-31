# Complete-.netcore3.1-MVCApplication
Complete .net core 3.1 MVC application

Required Software for this application.
---------------------------------------
1. Visual Studio 2019
2. Microsoft Sql server 2019 or 2017

Steps to run the application.
-----------------------------
Step 1: Clone the project or download as zip file.
Step 2:Extract all the file if you download the solution.
Step 3:Once sucessfully clone the project.Check the framework version 3.1 or not.(double clock on the solution it open ".csproj" there you can see the framework version.)
Step 4:Change the databse name and server as per your requirement in the "appsettings.json" file.
Step 5:After changed the databse name and server name run the below 2 commands to generate the migratations.
         --> To run the commands you need to open Package manager console.after that type below commands.
         --> PM>Add Migration Give SutiableName as per your Rrequirement
         -->Eg: PM>Add Migration initialcommit
         -->After enter the command click on "Enter" button. It will generate the Migration folder stracture.
         -->Once the migratation is completed successfully.go for next command
         --> PM>Update Database
         -->Eg: PM>Update Database
         -->Once the commnad is completed successfully.
Step 6:Run the application you can see the output.
         
 
 
