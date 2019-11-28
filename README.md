JIT Team Final Project

COCKTAIL MAGICIAN

The Project was developed in C#.Net, ASP.NET Core 2.2 MVC & SQL Server.
By application provides functionality for managing bars and cocktails and tracking their popularity among users.
Three Roles are introduced in the project:

=>User – can browse through all available information for bars and cocktails, and can also leave ratings and comments, and like other people’s reviews.

=>Manager – can perform all CRUD operations over the Bar and Cocktail entities. Also has permission to perform all operations of the User. 

=>Administrator – Extends the functionality of the Manager. The Admin has right to upgrade normal User to Manager and to delete users from the system. On top of that the Admin receives notifications when someone creates or deletes Bar or Cocktails, and receives the messages from the contact form.

Project Description:

The project Coctail Magician has various pages. Home page is the one where users can browse through. The layout of this page is designed to make it a user friendly as possible. A navigational menu is provided to link to top rated bars and cocktails pages. The users who desire to participate in the reviewing process have to register themselves at the site.

The Cocktails module is used for presenting information  for all available cocktails. A List of all cocktails is provided with available functionality for adding new cocktails, edit and delete for existing. A downloadable copy of the recipe is available. The Details page contains all the information about the the cocktails and an interactive map integrated through Gmail API for detecting the location of the bars offering the cocktail. 

The Bars module is used for listing all bars registered in the system. Functionality for add, edit and delete is also provided. Each Bar includes a map with the specific location of the bar. 
The Ingredients module shows all ingredients currently used in the recipes of the Cocktails. The Ingredients can be edited, and the ones not used in cocktails can be deleted. An interactive search bar is implemented. 

The search is performed through:
=>	Bars: by Name, Address and Rating;
=>	Cocktails: by Name, Ingredient/s and Rating;
All views that list entities use server-side pagination and more results are loaded with Ajax.

The business logic of the project has been test with unit tests to ensure the smooth flow of the provided functionality. 

All possible errors are handled with messages and  custom error pages.

A quick contact form is implemented, to grant the possibilities to visitor to send messages to the administrator.

The system was developed by Julia Stoimenova and Todor Karamfilov
