# CRUDforContacts_EECE439

## Description

A simple Django application for managing personal contacts, enabling users to perform CRUD operations (Create, Read, Update, Delete) on contacts data. Contacts can be added, viewed, edited, and deleted through an intuitive UI.

## Features

- **Add New Contact**: Save new contacts with details like name, address, profession, telephone number, and email.
- **View Contacts**: View all saved contacts in a structured table.
- **Edit Contact**: Modify the details of existing contacts.
- **Delete Contact**: Remove contacts that are no longer needed.

## Installation and Setup

### Prerequisites
- Python (3.6 or higher)
- Django (3.0 or higher)

### Steps
1. **Clone the Repository**: 
   ```sh
   git clone https://github.com/omarelturk/CRUDforContacts_EECE439
   cd CRUDforContacts_EECE439

   
2. Install Dependencies:
Ensure you have Python and Django installed. If not, install Django using:
pip install django

3. Database Migrations:
Apply the database migrations.
python manage.py migrate

4. Create Superuser:
Create an admin superuser to manage the app through Django admin.
python manage.py createsuperuser

5. Run Development Server:
Start the Django development server.
python manage.py runserver

6. Access the App:
Visit http://127.0.0.1:8000/ to interact with the app UI.
Visit http://127.0.0.1:8000/admin and log in with the superuser credentials to access the admin panel.

Usage

Adding a Contact
Navigate to Add New Contact.
Fill in the required fields: Name, Address, Profession, Telephone, and Email.
Click Save.
Viewing Contacts
All saved contacts are visible on the main page in a tabulated format.
Editing a Contact
Find the contact you wish to edit in the table.
Click Edit and modify the necessary fields.
Click Save.
Deleting a Contact
Find the contact you wish to delete in the table.
Click Delete and confirm the deletion.
Contributing

Feel free to fork the project, create a feature branch, and send us a pull request.

Acknowledgements

Thanks to all contributors and their valuable input to the project.


