# -CSharp-CRUD-For-Theater-Website

# Introduction
During this two week sprint I worked on an ASP.NET MVC C# project with a code first Entity Framework Database. Being able to work on a project in the middle of its lifecycle allowed me to collaborate with other developers on the project and see how they were able to solve problems, create features, and see how all the different functions of the program came together. I worked on the back end and front end of the CRUD for the create and edit pages.

## First tasks was to to use JavaScript to count the number of names of the developers that have worked on this project and display them next to the title and to use a bootstrap badge to style the number. (FrontEnd)
![](images/NumOfDevs.png)

### Code for the span with id="NumPersons." So that it may be dynamically updated with JavaScript to display a number of developers. The classes "badge" and "badge-secondary" are used in Bootstrap to style the span as a badge with a secondary appearance.
![](images/SignInCode.png)

### Code for the JavaScript to count the numbers of devs.
![](images/JSForNum.png)

## Second task was to create entity model for Rental and CRUD pages. (BackEnd)
This required me to create an enity model for the Rental class so that rentals can be saved to the database. Create the Rental class along with RentalEqupiment and RentalRoom classes. RentalEqupiment and RentalRoom should inherit from Rental. After that, create the controller and scoffold the CRUD pages for it. I used the EnitityFramework to create the Index, Edit, Create, Details anf Delete pages and added the Layout.cshtml as a layout page. 

 ### Code for classes
 ![](images/rental(model).png)

Using NuGet Package Manager Console, I was able to update the database to create the table with the rental, RentalEquipment and RentalCost. This program had automatic migrations enabled. Within the Controllers, I then added a new MVC5 Controller with views using Entity Framework, including a layout page. This created the neccessary CRUD pages for create and edit pages.

## Third task was to style the create and edit page. (FrontEnd)
- Add a header above the form with "Create Rental" on a single line.
- Style the Submit and Back to List Buttons with a color distinction between the two.
- Add placeholders to all input fields
- Change the input fields border when clicked to match the theme of the website and the color input field to change when clicked as well.
![](https://github.com/Jalen-Allison/-CSharp-CRUD-For-Theater-Website/blob/main/images/AnimationStylingStory1.gif)

## Fourth task was to Create & Edit for inherited classes. (FrontEnd & BackEnd)
Create a dropdown on the Create and Edit pages for selecting one of the Rental types. Depending on what the user chooses in the dropdown, show/hide input fields in the form. The create and Edit methods should be able to create or edit Rentals, RentalsEquipment, and RentalRooms.
(rDropDown) This is to link the rental types and for creating the dropdown list.
