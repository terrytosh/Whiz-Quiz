# Whiz-Quiz

## Purpose

This purpose of this website is to provide educational assistance for Computer Architecture students.  
The particular topic covered is processor data path and control. We have several quizzes that  
test your knowledge in this area. Feedback for correct and incorrect answers will be provided  
so that students are able to understand what they did right or wrong.  

## Requirements

click==8.1.2  
colorama==0.4.4  
Flask==2.1.1  
itsdangerous==2.1.2  
Jinja2==3.1.1  
MarkupSafe==2.1.1  
Werkzeug==2.1.1  

## Initial Setup and Execution

In order to run this website on your local machine. Please follow the instructions outlined below.  
Make sure to have Python installed on your machine. This can be verified in the command prompt with:  
> python --version  

If Python is not installed, navigate to ***https://www.python.org/downloads/*** and install it.  

First, clone the repository on your system using git clone.  

Now, we must set up the virtual environment.  
In the project directory:  
> py -3 -m venv venv  

> .\venv\Scripts\activate  

The virtual environment is now properly setup.  

Next, we must install Flask.  
In the project directory:  
> pip install flask  

To start the flask server and run the application:  
> python "app.py"  

In the command prompt, a local URL will be generated for the website to run on.  
For the most part, it will always be ***http://127.0.0.1:5000***  
Lastly, enter a browser of your choice and navigate to the specified URL.  
