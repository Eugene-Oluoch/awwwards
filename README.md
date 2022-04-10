# Awwwards Clone

A web app that allow users to post their projects to be rated

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Django and Python Needed
```

First you need to clone this project to your local machine 

```
git clone https://github.com/Eugene-Oluoch/awwwards.git
```

### Installing

First we install virtualenv and activate it

To install it run the command
```
pip3 install virtualenv
```

After the installation is done, now its time to activate the env

```
source env/bin/activate
```

Next we need to install all the requirements for the project from the requirements.txt file

```
pip3 install -r requirements.txt
```

Now its time to run the code

```
python3 manage.py runserver
```
## Screenshot

![Screnshot](https://github.com/Eugene-Oluoch/instagram-clone/blob/master/static/images/website%20screenshots/instagram.png)

This is landing page

![Screnshot](https://github.com/Eugene-Oluoch/instagram-clone/blob/master/static/images/website%20screenshots/instagram.png)

This is the signup page

![Screnshot](https://github.com/Eugene-Oluoch/instagram-clone/blob/master/static/images/website%20screenshots/instagram.png)

This is the login page

![Screnshot](https://github.com/Eugene-Oluoch/instagram-clone/blob/master/static/images/website%20screenshots/instagram.png)

This is the form for submitting  your project

![Screnshot](https://github.com/Eugene-Oluoch/instagram-clone/blob/master/static/images/website%20screenshots/instagram.png)

This is the  user profile

![Screnshot](https://github.com/Eugene-Oluoch/instagram-clone/blob/master/static/images/website%20screenshots/instagram.png)

This is the single project view


![Screnshot](https://github.com/Eugene-Oluoch/instagram-clone/blob/master/static/images/website%20screenshots/instagram.png)

This is the form for rating a project
##Extra

To use my api navigate to this urls

To retrieve user profile data

```
awards-eugene.herokuapp.com/api/profiles/
```


To retrieve all the projects

```
awards-eugene.herokuapp.com/api/projects/
```
## Built With

* [Python](https://docs.python.org/3/download.html) - The language mostly used
* [Django](https://maven.apache.org/) - The framework used
* [Cloudinary](https://cloudinary.com/) - Used for image upload
* [Heroku](https://www.heroku.com/) - Used for deployment


## Contact details
Email: eugenemarkke@gmail.com
## MIT licence

<p>Copyright (c) 2022 Moringa School </p>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.