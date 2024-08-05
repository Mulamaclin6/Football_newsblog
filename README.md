# Football_newsblog
This is a football transfer news blog app I first created using Django framework
# My Blog Project

## Setup

#Clone the repository:
```bash
git clone <repository_url>
cd blog

#Create a virtual environment and activate it:
```bash
python -m venv myenv
source myenv/Scripts/activate

#install Django on your virtual environment
```bash
pip install django

#Install the dependencies:
```bash
pip install -r requirements.txt

#start your project
```bash
django-admin startproject blogpr

#cd to your project
```bash
cd blogpr

#start your app
```bash
python manage.py startapp blog

#define Post Model in the app, 'models.py'

#Run the migrations:
```bash
python manage.py makemigrations
python manage.py migrate

#Create your views
a)To display list
b)To display details of a single post

#Setup Urls
a)Create urls.py in the blog app and define url patterns for the views
b)Include blog app's url in the project's urls.py

#Create templetes folder on the blog app
a)post_list.html
b)post_detail.html

#Use Django Admin to manage Posts
>Register the Post model with Django admin site in admin.py
>Use the admin site to add, edit and delete blog posts.

#Create a superuser to access the admin site:
```bash
python manage.py createsuperuser
Enter the required details:
You will be prompted to enter a username, email address, and password for the superuser. For example:
**Username** (leave blank to use 'your-username'): admin
**Email address**: admin@example.com
**Password**: ********
**Password** (again): ********
Superuser created successfully.

Run the development server:
```bash
python manage.py runserver

#Admin site
You can add a post
Edit the post
Delete the post
