<h1 align="center"><strong>Reddit Clone</strong></h1>

<img src="https://github.com/philliprognerud/Reddit-Clone/blob/master/images/iyDM8pl7dX.gif" align="center" >

<h2>Overview</h2>

Created a clone of Reddit built on the Django framework and bootstrap. Site is fully functional and any user can sign up for an account, login, create posts, upvote and downvote posts. 

## Getting Started

Get this project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Python 3.4 and up. We will be using modules such as pip, virtualenv, and Django. 


### Installing

Here is how to get your development envionment up and running with the dependencies.

1) Install Python.

```
https://www.python.org/
```

2) Check Python install is good.

```
Command: pip -V
```

3) Install Django! Run the command below.

```
Command: pip install django
```

4) Check Django install is good.

```
Command: python
>>> import django
>>> print(django.get_version())
```

5) Installing other dependecy, used for static images.

```
Command: pip install pillow
```

Once everything here has been properly installed, you should be able to deploy this website on your machine.

## Deployment

In order to deploy this application. Have the repo on your desktop ready to use. Open up the terminal and navigate to the working directory of the repo. Follow the commands below for your system. 

This is for windows 10 systems:
```
Command: .\venv\scripts\activate
(venv):  python manage.py runserver
```

This is for Mac/Linux systems:
```
Command: source /venv/scripts/activate
(venv):  python3 manage.py runserver
```

## Built With

* [Django](https://www.djangoproject.com/) - The web framework used
* [Atom](https://atom.io/) - Development Environment
* [Python3](https://www.python.org/) - Primary language

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Phillip Rognerud** - *Initial work* - [My GitHub Profile](https://github.com/philliprognerud)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.


## Acknowledgments

* Learned Django through online classes at udemy.com. Great website!
