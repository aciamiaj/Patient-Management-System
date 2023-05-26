# Patient-Management-System

The Patient Management System is a Windows Forms application that manages patient data in a laboratory management system. The form allows users to add, update, and delete patient records, search for patients by date, and view all patient data.

## Code Overview
The provided code snippet includes the following components:

Form Initialization: The Patient_Mastar_form class is a Windows Forms form that contains various controls for input and display of patient data. The form is initialized with default values and loads necessary data from the database.

Database Connection: The code establishes a connection to the Microsoft Access database using the OleDbConnection class. It also creates an OleDbCommand object for executing SQL queries.

Data Loading: The code includes methods to load test groups and doctors' data from the database into ComboBox controls.

Patient Data Loading: The loadPatientData method retrieves patient data from the database based on different search criteria and populates the patientGridView DataGridView control with the results.

Event Handlers: The code defines various event handlers for buttons, ComboBoxes, and DataGridView events. These event handlers perform actions such as adding tests to a ListBox, saving patient data to the database, updating and deleting patient records, and handling user interactions with the form.

Helper Methods: The code includes helper methods to generate patient IDs, switch between insert and update modes, and handle keyboard events.

## Usage
To use the Patient Management System , follow these steps:

Ensure that the necessary dependencies are included and the required classes and controls (Form, TextBox, ComboBox, ListBox, DataGridView, etc.) are available in your Windows Forms project.

Set up the database connection by replacing the connStr variable with the appropriate connection string for your Microsoft Access database.

Compile and run the application in a Windows Forms environment.

The form will be displayed with patient data loaded from the database.

Use the provided controls to search for patients by date or view all patients.

To add a new patient, enter the required information in the input fields and click the "Add" button to add tests to the ListBox. Then click the "Save" button to save the patient data to the database.

To update or delete an existing patient record, double-click on a row in the DataGridView to populate the input fields. Make the necessary changes and click the "Update" or "Delete" button to update or delete the record.

Use the "Clear" button to reset the input fields and switch back to insert mode.

The form provides additional functionalities such as generating patient IDs, handling keyboard events, and closing the form.

## Notes
Please note that the provided code snippet represents a part of the entire application. It is recommended to have the complete project solution and set up the necessary database schema and connections to run the application successfully.
