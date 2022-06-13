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

<img
  src="/images/server.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">
![Screenshot-2022-06-13-at-12-22-41.png](https://postimg.cc/8JYhN93R)
![Django](https://postimg.cc/nsPyfcH0)

_Error Warning_
![Unapplied migration](https://postimg.cc/dLRDsgZ8)

```python manage.py migrate```

