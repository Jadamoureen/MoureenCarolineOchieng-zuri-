# Zuri Django Project

### Instructions
1. Create a new Python virtual environment.
2. Initialize it, and install Django in it.
3. Create a new Django project.
4. Use your ZuriBoard username as the name of the project.

__Navigate to where you want to store your code__.
_Create new directory_

```mkdir my_project && cd my_project```

__Install virtual environment__

```pip install virtualenv```

__Start virtual evironment (named zurienv)__

```virtualenv zurienv```

__Activate virtual environment__
_For MAC OS_

```source zurienv/bin/activate```

_For windows OS_

```source zurienv/Scripts/activate```

__Install django__

```pip install django```

__Start your project__

```django-admin startproject moureencarolineochieng```

__Run the server__

```python manage.py runserver```

![server](server.png)
![Django](django.png)

_Error Warning_
![migration](migration.png)

```python manage.py migrate```

