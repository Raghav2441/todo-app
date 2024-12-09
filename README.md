To-Do List Application

This is a simple to-do list web application built using Django. It allows users to add tasks and view a list of existing tasks. It's a great project for anyone learning Django and looking for a basic web application to practice with.

Getting Started
To get started with this project, first clone the repository to your local machine using the command:

git clone https://github.com/yourusername/todo-app.git
Once you've cloned the project, navigate into the project directory:

cd todo-app
Next, it’s recommended to create a virtual environment to manage dependencies:

python -m venv venv
Activate the virtual environment:

On Windows: venv\Scripts\activate
Then, install the required dependencies by running:

pip install -r requirements.txt
After that, apply the database migrations with:

python manage.py migrate
Finally, start the development server:

python manage.py runserver
The app should now be running locally at http://127.0.0.1:8000. You can add tasks by going to the “Add Task” page and view all tasks on the homepage.

Project Structure
The project is structured in a typical Django setup, with the main app (todo) containing the models, views, and templates. The database is stored in db.sqlite3, and all project settings are in the todo_project/ directory. You'll also find a manage.py file for running management commands.

Troubleshooting
If you encounter issues, make sure to run migrations with python manage.py makemigrations and python manage.py migrate. If the server doesn’t start, ensure you’re in the correct directory and that the server is not already running on another port.

Contributing
Feel free to fork the project, create a new branch for any changes, and submit a pull request. Contributions are always welcome!

