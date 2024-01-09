Contacts Book Application Documentation
Introduction
The Contacts Book application is a simple Tkinter-based Python program that allows users to manage a list of contacts. It provides functionalities to add, delete, copy phone numbers, save the contact list to a file, and open a saved file.

Features
Contact Management:

Add Contact: Enter first name, last name, phone number, and email, and click "Add Contact" to add a contact to the list.
Delete Contact: Select a contact from the list and click "Delete Contact" to remove it.
Copy Phone Number: Select a contact, click "Copy Phone Number," and the phone number will be copied to the clipboard.
File Operations:

Save List: Click "Save List" to save the contact list to a text file named "saved.txt."
Open Saved File: Click "Open Saved File" to load contacts from a saved text file.
User Interface:

Clean and intuitive user interface with entry fields, buttons, and a listbox for displaying contacts.
Labels and entry fields for entering contact information.
Responsive buttons for performing actions.
Database Integration
The application uses SQLite to create and manage a database named Contacts.db. The database has a table named CONTACT with columns: id (primary key), first_name, last_name, phone, and email.

Functions
Communication Function:

communication(interface, *args): Executes SQLite database queries and returns the result.
Database Initialization:

create(): Creates the CONTACT table if it doesn't exist.
Contact Operations:

insert(): Inserts contact information into the database.
delete(): Deletes a contact from the database.
Information Handling:

add_info(): Formats and adds contact information to the listbox.
File Operations:

save_info(): Saves the contact list to a file named "saved.txt."
open_file(): Opens a saved file and populates the contact list.
User Interface Functions:

create_label(): Creates labels in the UI.
create_entry(): Creates entry fields in the UI.
create_button(): Creates buttons in the UI.
Application Control:

exit_app(): Prompts the user to confirm application exit.
Usage
Adding Contacts:

Enter first name, last name, phone number, and email.
Click "Add Contact" to add the contact to the list.
Deleting Contacts:

Select a contact from the list.
Click "Delete Contact" to remove it.
Copying Phone Numbers:

Select a contact from the list.
Click "Copy Phone Number" to copy the phone number to the clipboard.
Saving and Loading Contacts:

Click "Save List" to save the contact list to a file.
Click "Open Saved File" to load contacts from a saved file.
Exiting the Application:

Click "Exit App" to close the application.
File Structure
Database: Contacts.db
Saved File: saved.txt
Dependencies
Python 3.x
Tkinter library
How to Run
Ensure you have Python installed on your system.
Run the Python script containing the Contacts Book code.
"python contacts_book.py"
