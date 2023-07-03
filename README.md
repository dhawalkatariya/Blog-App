
# Blog App Django
This is a simple blog application developed using Django, a high-level Python web framework. The application allows users to create, read, update, and delete blog posts.

## Prerequisites
Before running the application, ensure that you have the following installed:

* Python (version 3.6 or higher)
* Django (version 3.2 or higher)

## Installation
1. Clone the repository to your local machine:
```
  $ git clone https://github.com/dhawalkatariya/Blog-App
```
2. Change to the project's directory:
```
  $ cd Blog-App
```
3. Install the required dependencies using pip:
```
  $ pip install -r requirements.txt
```

## Configuration
1. Create a new file named .env in the project's mysite directory using .env.template.
2. Add the following line to the .env file:
```
  SECRET_KEY=your-secret-key
```
Replace your-secret-key with a unique and secure secret key. You can generate a secret key using Django's django.core.management.utils.get_random_secret_key() function.


## Database Setup
By default, the application uses a SQLite database. If you prefer to use a different database, update the DATABASES configuration in the settings.py file.

1. Create the necessary database tables by running the following command:
```
  $ python manage.py migrate
```

## Usage
1. To start the development server, run the following command:
```
  $ python manage.py runserver
```
2. You should see output similar to the following:
```
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```
Open your web browser and visit http://127.0.0.1:8000/ to access the blog application.

## Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
