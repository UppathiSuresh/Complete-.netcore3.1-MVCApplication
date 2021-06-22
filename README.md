# Complete-.netcore3.1-MVCApplication
Complete .net core 3.1 MVC application

Required Softwares for this application.
---------------------------------------
1. Visual Studio 2019
2. Microsoft Sql server 2019 or 2017

Steps to Run the Application.
-----------------------------
Step 1: Clone the project or download as zip file.
Step 2:Extract all the file if you download the solution.
Step 3:Once sucessfully clone the project.Check the framework version 3.1 or not.(double clock on the solution it open ".csproj" there you can see the framework version.)
Step 4:Before go to next step check the required pakcage you have or not.packages to check "Microsoft.EntityFrameworkCore","Microsoft.EntityFrameworkCore.SqlServer" and
       "Microsoft.EntityFrameworkCore.Tools"
Step 5:Change the databse name and server as per your requirement in the "appsettings.json" file.
Step 6:After changed the databse name and server name run the below 2 commands to generate the migratations.
         --> To run the commands you need to open Package manager console.after that type below commands.
         --> PM>Add Migration Give SutiableName as per your Rrequirement
         -->Eg: PM>Add Migration initialcommit
         -->After enter the command click on "Enter" button. It will generate the Migration folder stracture.
         -->Once the migratation is completed successfully.go for next command
         --> PM>Update Database
         -->Eg: PM>Update Database
        -->Once the commnad is completed successfully.
Step 7:Run the application you can see the output.
         
 
#OutPut Screen shot. 
![image](https://user-images.githubusercontent.com/25552209/122875813-61694500-d352-11eb-8d6a-4b9a5f2743fe.png)
