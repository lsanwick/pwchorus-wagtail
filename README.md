# www.pwchorus.org

Wagtail-based website for Peninsula Women's Chorus

## Installation

### Set up a Python virtualenv

On Windows (cmd.exe):

    $ python3 -m venv mysite\env
    $ mysite\env\Scripts\activate.bat

On Unix or MacOS (bash):

    $ python3 -m venv mysite/env
    $ source mysite/env/bin/activate

### Install project dependencies

    $ pip install -r requirements.txt

### Create a superuser account for yourself

    $ python manage.py createsuperuser

### Start the server

    $ python manage.py runserver

View the site at http://localhost:8000
