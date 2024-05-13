Recipe Management System
This command-line application allows users to manage multiple recipes efficiently. It fulfills the following functionalities:

Inputting Recipes:

Users can input details for multiple recipes including ingredients, steps, calories, and food groups.
Scaling Recipes:

Recipes can be scaled by a factor of 0.5, 2, or 3, adjusting ingredient quantities accordingly.
Viewing Recipe List:

Users can view a list of all recipes sorted alphabetically by name and select a recipe to view its details.
Calorie Monitoring:

The system calculates and displays the total calories of each recipe and notifies the user if it exceeds 300 calories.
Resetting and Clearing Data:

Users can reset ingredient quantities to original values or clear all data to input a new recipe.
Implementation Details:
Classes:

Recipe: Manages recipe details, scaling, and calorie calculation.
Ingredient: Represents ingredients with name, quantity, unit, calories, and food group.
Step: Represents steps with descriptions.
RecipeBook: Manages multiple recipes.
Data Storage:

Utilizes generic collections like List<T> for storing recipes, ingredients, and steps.
User Interaction:

Utilizes command-line interface for user input and display.
Calorie Notification:

Uses a delegate to notify users when a recipe's total calories exceed 300.
Unit Testing:
Includes unit tests to ensure accurate calculation of total calories.
Coding Standards:
Follows internationally acceptable coding standards with comprehensive comments explaining variable names, methods, and logic.
How to Run:
Clone the repository.
Open the solution in Visual Studio.
Build the solution.
Run the application from the command line.
Follow the on-screen instructions to manage recipes.
This system provides a convenient way for users to manage and monitor their recipes, ensuring they meet their dietary requirements.
