url_shortener
O(1) Coding Club final Task (URL Shortener Django project)

Django URL Shortener with View Counts
This is a simple URL shortener web application built with Django that also tracks and displays the view counts for each shortened URL. With this application, you can easily create short URLs for long links and monitor how many times each URL has been accessed.

Table of Contents
Features
Requirements
Installation
Usage
Managing Shortened URLs
Contributing
License
Features
Shorten long URLs to more manageable, concise links.
Track and display view counts for each shortened URL.
User authentication for creating and managing shortened URLs.
An admin panel for superusers to oversee the application.
Clean and responsive design using Django's built-in templating system.
Requirements
Before you begin, ensure you have met the following requirements:

Python 3.x
Django 3.x or higher
A compatible database (e.g., PostgreSQL, MySQL, SQLite)
Installation
Clone the repository to your local machine:
git clone https://github.com/your-username/url-shortener.git
cd url-shortener
Create a virtual environment (optional but recommended):
python -m venv venv
Activate the virtual environment:

On Windows:
venv\Scripts\activate
On macOS and Linux:
source venv/bin/activate
Install the project dependencies:

pip install -r requirements.txt
Set up the database by running migrations:
python manage.py makemigrations
python manage.py migrate
Create a superuser account to access the admin panel:
python manage.py createsuperuser
Start the development server:
python manage.py runserver
Access the application in your web browser at http://localhost:8000.
Usage
Register or log in as a user to access the URL shortening functionality.

To create a short URL, go to the "Shorten URL" page, enter the long URL, and click "Shorten."

You will receive a shortened URL that redirects to the original URL, along with the view count.

Managing Shortened URLs
To manage shortened URLs, you can log in as a user and go to the "My URLs" page.
You can view a list of your shortened URLs, including their view counts.
Edit or delete your shortened URLs as needed.
Contributing
We welcome contributions from the community. If you want to contribute to this project, please follow these steps:

Fork the repository on GitHub.
Clone your forked repository to your local machine.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push your branch to your fork on GitHub.
Create a pull request from your branch to the main repository.
