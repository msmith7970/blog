# Project - The Blog


## SCOPE

The purpose of the project is to create a Multi User Blog application using the
Google App Engine framework and to deploy it where it is publicly accessible.
The blog is currently set up to function as a single blog but can easily be
modified to function as a Multi Blog.  

## Usability

The application can be accessed by going to
[theblog-170323.appspot.com](https://theblog-170323.appspot.com)

From the home page the user has an option to login or if they are a new user
they have the option to signup to become a registered user. Once logged in they
will then have a logout option.

Users are stored in a database where usernames are unique and stored passwords
are hashed for security purposes. When users are successfully signed in a
secure cookie will be set that will be used to identify the user throughout the
site.

A user can create a post. Once a post is created, from the blog page the user
will have the option to edit and delete a post, but they may only do so for one
they created themselves. When editing or deleting a post the user will have the
option to cancel that request by hitting a cancel button.

A signed in user can comment on posts and may only edit and delete comments they
themselves have made. Similar to the post when editing or deleting a comment the
user will have the option to cancel that request by hitting a cancel button.

A user will also have the option to like a post once and will not be able to
like their own post.


## Setup

On your PC you will need to have the following Applications Set up and
Installed on your PC:

* Install [Python](https://www.python.org/downloads/).
* [Install Google App Engine SDK for Python]
(https://cloud.google.com/appengine/docs/standard/python/download).
* [Sign Up for a Google App Engine Account](http://cloud.google.com/appengine).
* Create a new project in [Google's Developer Console]
(https://console.cloud.google.com) using a unique name.  (For example: blog)
* Install [Jinja](http://jinja.pocoo.org/).  Jinja is used to create templates
 and helper functions.
* Install and Set up [Git](https://help.github.com/articles/set-up-git/)


## Download Files From GitHUb

Download and install the following items from GitHUb to a PC that can be viewed
using the Google Chrome Web Browser.

These items include:

    1) app.yaml - This is used with the google app engine.
    2) blog.py - This is the python file containing all the code for the blog
       application.
    3) templates folder - Contains all the templates used by the blog application.
    4) css folder - This is a folder containing the css file called main.css.
    5) README.md

 ## To configure the application on your PC

* Get all the items from Setup listed above installed and running.

* Open a command line editor on your PC and create a new folder on your PC
that will be used to clone the blog GitHub repository into locally on your
machine.

* Clone the GitHub repository by navigating to the newly created folder by the
following:

 1. Goto GitHub at https://github.com/msmith7970/blog
 2. Under the repository name, Click "Clone or download"
 3. In the Clone with HTTP section, click the "Copy to clip board" option to
copy the clone URL for the repository.
 4. Open Git Bash and navigate to the folder you created to store the repository
in.
 5. Type ** git clone ** and then past the URL you copied.  It will look like the
following:

          $ git clone https://github.com/msmith7970/blog

 6.  Press **Enter** and your local clone will be created.  You will now have a
local copy of your fork of the blog repository.


* On the command line editor in your new directory, start the Python Web Server
by typing the following:

      > dev_appserver.py .

* Open Google Chrome browser and navigate to the local server by typing the
following URL:

      http://localhost:8080

* You are now connected to the blog.


## Google Chrome

To install Google Chrome, visit:
[Google Chrome](http://www.browserwin.com/web/ "Google Chrome")
and follow the download instructions.


## License

The content of this repository is licensed under MIT License.

Copyright (c) 2017 Mitchell Smith

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
