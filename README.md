# Todo_list

#### <div dir="rtl">By **Catherine Wangui**</div>

## Description
A web application to post to do list items
## Features
* Users create an account.
* Users can log in to create their to do list items once they have an account.
* Users can view to do list items that they are yet to complete
* Users can search to do list items by title.

# Specifications


## Setup/Installation Requirements
Here is a run through of how to set up the application:
* Step 1 : Clone this repository using the git clone link:
  * **`git clone https://github.com/catekui/todo_list.git`**
* Step 2 : Navigate to the directory:
  * **`cd todo_list`**
* Step 3 : Open the directory created with your favorite IDE. If Atom type **`atom .`** if VSCode type **`code .`** . This will launch the editor with the project setup,
* Now feel free to hack around the project.

## Getting started
### Prerequisites
* python
* virtual environment
* pip

### Cloning
* In your terminal:

       $ git clone https://github.com/catekui/todo_list.git

## Running the Application
* Install virtual environment using `$ python3 -m venv --without-pip virtual`
* Activate virtual environment using `$ source virtual/bin/activate`
* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
* Install all the dependencies from the requirements.txt file by running `python3 pip install -r requirements.txt`
* Create a database and edit the database configurations in `settings.py` to your own credentials.
* Make migrations

        $ python manage.py makemigrations photos
        $ python3 manage.py migrate 

* To run the application, in your terminal:

        $ python3 manage.py runserver
        
        
## Technologies Used
- Python 
- Django MVC framework
- HTML, CSS and Bootstrap
- Postgressql
- Heroku

### License
[MITlicense](LICENSE) 2022