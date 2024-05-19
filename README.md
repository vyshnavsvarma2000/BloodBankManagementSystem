Blood Bank Management System
Welcome to the Blood Bank Management System project repository. This project is a comprehensive solution designed to manage blood bank operations effectively. The system is built with a user-friendly interface using HTML, CSS, and JavaScript, and is powered by Django on the backend, with additional enhancements provided by django-widget-tweaks.

Features
Donor Management: Register and manage donor information.
Recipient Management: Track and manage recipients' details.
Inventory Management: Keep track of blood stock, including different blood types and quantities.
Request Handling: Manage blood donation requests and fulfill recipient needs efficiently.
Authentication: Secure login and registration system for different user roles.
Responsive Design: Accessible on various devices with a responsive layout.
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Django
Enhancements: django-widget-tweaks

Installation
To set up the project locally, follow these steps:

Clone the repository:
https://github.com/vyshnavsvarma2000/BloodBankManagementSystem.git
cd bloodbank

Create a virtual environment:
python3 -m venv env
source env/bin/activate   # On Windows use `env\Scripts\activate`

Install the dependencies:
pip install -r requirements.txt

Run the migrations:
python manage.py migrate

Start the development server:
python manage.py runserver


Access the application:
Open your web browser and go to http://127.0.0.1:8000/.


Requirements
The project requires the following packages to be installed:

asgiref==3.2.7
Django==3.0.5
django-widget-tweaks==1.4.8
pytz==2020.1
sqlparse==0.3.1
These dependencies are listed in the requirements.txt file and can be installed using pip.

Usage
Once the server is running, you can interact with the Blood Bank Management System through the web interface. The system provides various functionalities to manage donors, recipients, and blood inventory. Admin users have additional capabilities to manage the overall system settings and data.

Contributing
We welcome contributions to enhance the Blood Bank Management System. To contribute:

Fork the repository.
Create a new branch for your feature or bugfix.
Make your changes and commit them with descriptive messages.
Push your changes to your forked repository.
Create a pull request to merge your changes into the main repository.


License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For any questions or inquiries, please feel free to reach out through the repository's issue tracker or contact me directly at your-vyshnav.s.varma@gmail.com.

Thank you for using the Blood Bank Management System!


