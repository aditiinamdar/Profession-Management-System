Figma Link: Project Overview Link

Tasks:

Create a simple form with three inputs: name, profession, and age. All fields are required.
Display a default view with 0 added employees.
Implement event handlers:
Add Employee: On click of this button, append an object into an array.
Show Added Employees: Map the array to display the data below the "Added Employees" section.
Show Error Message: Display a red error message if the required fields are empty.
Show Success Message: Display a green success message if the fields are filled and the employee was added successfully.
Delete User: On click of this button, remove the specific object from the array and hide the corresponding div.
Project Structure:

The structure of the array should be as follows:

[
  {id: 1, name: "Jack", profession: "Developer", age: 20},
  {id: 2, name: "John", profession: "Admin", age: 28},
  // More objects can be added similarly
]
Evaluation Criteria
Part 1: User Interface
Form Inputs: There should be three inputs for name, profession, and age.
Add Employees Button: There should be a button to add employees.
List of Added Employees: The UI should display a list of added employees.
Error and Success Messages: Error messages should be displayed in red, and success messages in green.
Part 2: Error Messages
Empty Fields: A red error message should appear when required fields are empty.
Part 3: Success Message
Filled Fields: A green success message should appear when fields are filled, and the employee is added successfully.
Part 4: Add Employee Function
Appending Object: The onClick function should append an object into an array with name, profession, and age.
Unique ID: The onClick function should automatically generate a unique ID for each employee.
Part 5: Mapping of Added Employees
Mapping: The array of added employees should be mapped to show the data below the "Added Employees" heading.
Part 6: Deleting Users
Delete Button: There should be a delete button for each added employee.
Object Removal: The object should get removed from the array on clicking the delete button, and the div should disappear.
Demo Project Link: Demo Project Link
