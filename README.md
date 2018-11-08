# School-Projects
School Projects


ClassRegistration Zip: 
ASP.NET Web Forms project for a school classes registration application. It has a master page and several content pages, most of which use a code behind. The master page contains an internal style sheet shared by all content pages, including a menu for navigation. Most pages query a SQL Server database to display class information. To view the Register and MyClasses pages, you must be logged in via the Login page, otherwise you are redirected to the Login page. Login state is maintained via a Session variable. To obtain credentials, use the NewLogin page, which will write an access request to the database. Login page queries the database to validate credentials. The Register screen displays available classes, and facilitates registering by displaying a checkbox for each class, and a button to register for all selected classes. MyClasses displays the classes for which you have registered. All database access is done via C Sharp classes stored in the App_Code folder. Abstraction layers: The Presentation layer is achieved by having the UI in the content pages, and the Processing layer code to access the database is in the App_Code folder, which calls the stored procedures and views (with no direct database access) in the SQL Server database (Data layer). Written using Visual Studio 2015 Community.



