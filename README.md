# Overview

I am building a website using Django as my framework so I can become more well rounded in my technical knowledge. I have never used Django until this project, so it was a great learning experience. This has helped me to realise that there are a ton of helpful tools, libraries, and frameworks that I could use for my future projects.

I created a Portfolio web app that displays my projects that I have worked on. To start the test server, you have to open up a terminal in the folder that contains the website "Portfolio_Website". Then you need to type "python manage.py runserver" into the terminal to start the server. The url you need to type in to access the website is "http://localhost:8000/". This will take you to the introduction page, where you can then nagivate to the projects page.

My purpose for writing this software is to learn about how to create websites and how to host them. I need to become more well rounded in my coding knowledge, so learning how to make web apps is my first step in this journey.

[Software Demo Video](https://youtu.be/OWMkzAJ5qXw)

# Web Pages

The home page introduces me, summarizes my technical experience, and displays a button to take you to my projects tab.

The projects tab dynamically creates the project cards using a loop. A project is added from the admin page of Django, and is stored in a database managed by Django. Django pulls from this database to create the project cards. There are read more buttons that take you to a separate page that goes into greater detail of the individual project. There is another button that can take you back to the home page.

The project details page also dynamically pulls info from each project's data from the database. It has the title, category, description, techonogy tags, image gallery, and Github link. There is a button that will take you back to the main projets tab.

# Development Environment

* Tools used: Django and Codex

* Disclaimer: Codex was used to help set up the framework of Django and for debugging.

* Language: Python

* Libraries: Bootstrap

# Useful Websites

* [RealPython](https://realpython.com/get-started-with-django-1/#start-your-first-django-project)
* [GeeksForGeeks](https://www.geeksforgeeks.org/python/python-web-development-django/)

# Future Work

* Add a good background image to help bring more life to the page
* Improve the project cards so they look more uniform
* Be able to add more photos for each project, so you can scroll between them
