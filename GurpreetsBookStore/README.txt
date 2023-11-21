11/13/2023
6:50PM
Create project again,
did smothing wrong
Create project GurpreetBookStore
modify the line7 in launchSettings.json
Modify Startup.cs
create git repo
add readme.txt file
add readme.md file
try commit the changes in readme.text but it shows pull failed that close the visual studio, clone the repo and then add readme and commit the changes, it works:)
go through every folder those created itself 

7:15PM
Starting the bootstrap step
select theme
download bootstrap.css
rename the original file bootstrap.css to bootstrap1.css

replace the code site.css
change the _layout.cshtml

Run the website, everything fine;)

modify Layout.cshtml
add a dropdown list named as content management
run code!!! Everything goes well:)
great relief!!

11/14/2023
2.1 Create the DB
build the application only for the confirmation that there are no errors:)
yes, its succeeded
review appsetting.json and create the migration by using pacakage manager console
It shows me error than I recognize that it is is kashishBooksStore project 


9:00AM, 
I will do this again but in .DataAccess
as I had older version and i got confused then I used alot of commands 
I install entity.FrameworkTools 

9:15AM
I think that I have to install package microfost.entityframewokrCore.tools-version 5.0.0
but again it was not working 
it works

9:45AM 
I commit it on github.
UPDATE MY DATABASE

10:11AM
check th errors,it works
adding migration and added to the  Db Context
rerunthe migration and update the database
starting the part-2 

10:15AM
modify the IRepository.cs so it can be used the category class to do all CRUD operations
adding an entity

11:09AM
add folder categoryrepository and icategoryrepository modify both of them and follow all your instruction
Complete the remaining modifications

11:28AM
ADDING A NEW INTERFACE NAMES AS isp_call.cs
modify it and also install dapper for this.
and adding a class sp_call.cs
add a connection to database

11/20/2023
7:00PM
Part 3 Section1
Add CoverType.cs in .models
Add migartion

7:10PM
The entity type 'CoverType' requires a primary key to be defined. If you intended to use a keyless entity type, call 'HasNoKey' in 'OnModelCreating'. For more information on keyless entity types, see https://go.microsoft.com/fwlink/?linkid=2141943.
Got this error when running the migration command again.
add covertypeid
and the error resolve

7:39PM
do repository step by following the category part of part2

7:57PM
Add covertype in the unitofwork and iunitofwork

8:13PM
CoverTypeController added same as category


