# Overview

{Important!  Do not say in this section that this is college assignment.  Talk about what you are trying to accomplish as a software engineer to further your learning.}

{Provide a description the web app that you wrote. Describe how to start a test server on your computer and what website to open up to see the first page of the app.}

{Describe your purpose for writing this software.}

{Provide a link to your YouTube demonstration.  It should be a 4-5 minute demo of the software running (starting the server and navigating through the web pages) and a walkthrough of the code.}

[Software Demo Video](http://youtube.link.goes.here)

# Web Pages

The home page introduces me, summarizes my technical experience, and displays my
featured projects. Django dynamically creates the project cards by looping over
the `PROJECTS` data passed to the template by the `home` view. This means that a
new project can be added to the Python data without copying and editing an entire
HTML card.

Selecting **View project details** on a project card transitions to that project's
detail page. Django includes the project's slug in the URL, such as
`/projects/ble-game-controller/`. The `project_detail` view uses that slug to find
the selected project and dynamically fills the same detail-page template with its
title, category, description, technology tags, image gallery, and GitHub link.
The **Back to portfolio** link returns to the home page. The image gallery also
uses a loop, so it will automatically create a figure for each image added to a
project's `images` list.

# Development Environment

{Describe the tools that you used to develop the software}

{Describe the programming language that you used and any libraries.}

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Web Site Name](https://realpython.com/get-started-with-django-1/#start-your-first-django-project)
* [Web Site Name](https://www.geeksforgeeks.org/python/python-web-development-django/)

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}
* Item 1
* Item 2
* Item 3
