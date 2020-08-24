* We have created this project using MVC Core 3.1 with have set authentication to Individual
* After this we have created 3 class Libraries to divide project: BulkyBook.DataAccess, BulkyBook.Models, BulkyBook.Utility
* After that we move data folder to .DataAccess and remove content of migrations
* After that moved ErrorViewModel.cs from Model folder to .Models in a folder ViewModels which we have created
* Then we will add all refrence by right clicking on main project and clicking add>references
* Then we will add .Model and .Utility refrence in .DataAccess
* Now creae a new area in area folder with name Customer and then change the routes
* Then change the pattern in Startup.cs>endpoints to {area=Customer}{controller=Home}/{action=Index}/{id?}
* Move HomeController to Areas>Customer>Controllers and explicitly mention above HomeController Class [Area("Customer")]
* Move HomeController Views to Areas>Customer>Views
* Since we have moved Views that's why we have to copy paste and change _ViewImports.cshtml and _ViewStart.cshtml
* Change path of _ViewStart.cshtml to Layout = "~/Views/Shared/_Layout.cshtml";
* Now we will create an Admin Area same as Customer and Delete Data and Models folder and add _ViewImports.cshtml and _ViewStart.cshtml also in Views




