# -CSharp-CRUD-For-Theater-Website

#Introduction
During this two week sprint I worked on an ASP.NET MVC C# project with a code first Entity Framework Database. Being able to work on a project in the middle of its lifecycle allowed me to collaborate with other developers on the project and see how they were able to solve problems, create features, and see how all the different functions of the program came together. I worked on the back end and front end of the CRUD for the create and edit pages.

## First task was to create entity model for Rental and CRUD pages. (BackEnd)
This required me to create an enity model for the Rental class so that rentals can be saved to the database. Create the Rental class along with RentalEqupiment and RentalRoom classes. RentalEqupiment and RentalRoom should inherit from Rental. After that, create the controller and scoffold the CRUD pages for it. I used the EnitityFramework to create the Index, Edit, Create, Details anf Delete pages and added the Layout.cshtml as a layout page. 
(rental model picture)
Using NuGet Package Manager Console, I was able to updat the database to create the table with the rental, RentalEquipment and RentalCost. This program had automatic migrations enabled. Within the Controllers, I then added a new MVC5 Controller with views using Entity Framework, including a layout page. This created the neccessary CRUD pages for create and edit pages.

## Second task was to style the create and edit page. (FrontEnd)
- Add a header above the form with "Create Rental" on a single line.
- Style the Submit and Back to List Buttons with a color distinction between the two.
- Add placeholders to all input fields
- Change the input fields border when clicked to match the theme of the website and the color input field to change when clicked as well.
(part1CRUD)

## Third task to Create & Edit for inherited classes. (FrontEnd & BackEnd)
Create a dropdown on the Create and Edit pages for selecting one of the Rental types. Depending on what the user chooses in the dropdown, show/hide input fields in the form. The create and Edit methods should be able to create or edit Rentals, RentalsEquipment, and RentalRooms.
(rDropDown) This is to link the rental types and for creating the dropdown list.
