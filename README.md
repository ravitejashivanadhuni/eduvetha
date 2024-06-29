# Contact Management System

This is a simple Contact Management System implemented in Python. The system allows users to add, view, edit, and delete contacts. It is designed to help understand basic Python concepts, file handling, and data structures.

## Features

- **Add Contact**: Add new contacts with name, phone number, and email.
- **View Contacts**: Display all saved contacts.
- **Edit Contact**: Edit the details of an existing contact.
- **Delete Contact**: Delete an existing contact.
- **File Handling**: Save contacts to a CSV file and load contacts from a CSV file when the program starts.

## Requirements

- Python 3.x

## Setup

1. **Install Python**: Ensure that Python is installed on your system. You can download and install Python from the official website: [python.org](https://www.python.org/downloads/).
2. **Save the Script**: Save the provided script as `contact_manager.py`.

## Running the Script

1. **Open Terminal or Command Prompt**: Open a terminal (on macOS or Linux) or Command Prompt (on Windows).
2. **Navigate to the Script Directory**: Use the `cd` command to navigate to the directory where you saved the `contact_manager.py` file. For example, if the file is saved in the `Documents` directory:
    ```sh
    cd Documents
    ```
3. **Run the Script**: Run the script by typing the following command:
    ```sh
    python contact_manager.py
    ```

## Usage

When you run the script, you will see a menu with the following options:

## Contact Management System

1.Add Contact
2.View Contacts
3.Edit Contact
4.Delete Contact
5.Exit
Enter your choice:

- **Add Contact**: Enter `1` to add a new contact. You will be prompted to enter the name, phone number, and email of the contact.
- **View Contacts**: Enter `2` to view all saved contacts. The contacts will be displayed in a list format.
- **Edit Contact**: Enter `3` to edit an existing contact. You will be prompted to select a contact to edit and update its details.
- **Delete Contact**: Enter `4` to delete an existing contact. You will be prompted to select a contact to delete.
- **Exit**: Enter `5` to save the contacts to a CSV file and exit the program.

## File Handling

- Contacts are saved to a CSV file named `contacts.csv` in the same directory as the script.
- When the program starts, it loads contacts from the `contacts.csv` file.
## How to Use

### Running the Script

1. **Open Terminal or Command Prompt**: Open a terminal (on macOS or Linux) or Command Prompt (on Windows).
2. **Navigate to the Script Directory**: Use the `cd` command to navigate to the directory where you saved the `contact_manager.py` file. For example, if the file is saved in the `Documents` directory:
    ```sh
    cd Documents
    ```
3. **Run the Script**: Run the script by typing the following command:
    ```sh
    python contact_manager.py
    ```

### Menu Options

When you run the script, you will see the following menu:


#### Adding a Contact

1. Enter `1` to add a new contact.
2. You will be prompted to enter the name, phone number, and email of the contact.
3. The contact will be added to the contact list, and a confirmation message will be displayed.

Example:
Enter your choice: 1
Enter name: John Doe
Enter phone number: 1234567890
Enter email: johndoe@example.com
Contact added successfully.

#### Viewing Contacts

1. Enter `2` to view all saved contacts.
2. The contacts will be displayed in a list format with their respective details.

Example:
Enter your choice: 2
Contacts List:

1.Name: John Doe, Phone: 1234567890, Email: johndoe@example.com

#### Editing a Contact

1. Enter `3` to edit an existing contact.
2. A list of contacts will be displayed.
3. Enter the number of the contact you want to edit.
4. You will be prompted to enter the new details for the contact. Leave the input blank to keep the current value.

Example:

Certainly! Here's an enhanced section for the README.md that provides detailed instructions on how to use the Contact Management System:

markdown
Copy code
## How to Use

### Running the Script

1. **Open Terminal or Command Prompt**: Open a terminal (on macOS or Linux) or Command Prompt (on Windows).
2. **Navigate to the Script Directory**: Use the `cd` command to navigate to the directory where you saved the `contact_manager.py` file. For example, if the file is saved in the `Documents` directory:
    ```sh
    cd Documents
    ```
3. **Run the Script**: Run the script by typing the following command:
    ```sh
    python contact_manager.py
    ```

### Menu Options

When you run the script, you will see the following menu:

Contact Management System

Add Contact
View Contacts
Edit Contact
Delete Contact
Exit
Enter your choice:
css
Copy code

#### Adding a Contact

1. Enter `1` to add a new contact.
2. You will be prompted to enter the name, phone number, and email of the contact.
3. The contact will be added to the contact list, and a confirmation message will be displayed.

Example:
Enter your choice: 1
Enter name: John Doe
Enter phone number: 1234567890
Enter email: johndoe@example.com
Contact added successfully.

css
Copy code

#### Viewing Contacts

1. Enter `2` to view all saved contacts.
2. The contacts will be displayed in a list format with their respective details.

Example:
Enter your choice: 2
Contacts List:

Name: John Doe, Phone: 1234567890, Email: johndoe@example.com
css
Copy code

#### Editing a Contact

1. Enter `3` to edit an existing contact.
2. A list of contacts will be displayed.
3. Enter the number of the contact you want to edit.
4. You will be prompted to enter the new details for the contact. Leave the input blank to keep the current value.

Example:
Enter your choice: 3
Contacts List:

1.Name: John Doe, Phone: 1234567890, Email: johndoe@example.com
Enter the number of the contact to edit: 1
Editing Contact: John Doe
Enter new name (leave blank to keep 'John Doe'): John A. Doe
Enter new phone (leave blank to keep '1234567890'):
Enter new email (leave blank to keep 'johndoe@example.com'): john.a.doe@example.com
Contact updated successfully.

#### Deleting a Contact

1. Enter `4` to delete an existing contact.
2. A list of contacts will be displayed.
3. Enter the number of the contact you want to delete.
4. The contact will be removed from the contact list, and a confirmation message will be displayed.

Example:
Enter your choice: 4
Contacts List:

1.Name: John Doe, Phone: 1234567890, Email: johndoe@example.com
Enter the number of the contact to delete: 1
Deleted Contact: John Doe

#### Exiting the Program

1. Enter `5` to exit the program.
2. The contacts will be saved to a CSV file named `contacts.csv`, and a confirmation message will be displayed before exiting.

Example:
Enter your choice: 5
Contacts saved. Exiting...

## License

This project is open source and available under the MIT [LICENSE](LICENSE)
