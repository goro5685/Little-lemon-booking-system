# Steps to Run the Project Locally

Follow these steps to run the project on your machine:

1. Unzip the project folder.

2. Navigate to the project directory using the command:
   ```
   cd <project directory>
   ```
3. Prepare the virtual environment and install all dependencies. To do this, first initiate the virtual environment using Pipenv:
   ```
   pipenv shell
   ```
4. Next, install the necessary dependencies:
   ```
   pipenv install
   ```
5. Make migrations for the database changes:
   ```
   python manage.py makemigrations
   ```
6. Apply these migrations:
   ```
   python manage.py migrate
   ```
7. Finally, run the server:
   ```
   python manage.py runserver
   ```
Now, your project should be running locally.