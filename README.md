# pwchorus-wagtail

Wagtail-based website for Peninsula Women's Chorus

### Installation

#### Prerequisites

- Python 3
- Postgres

Move your terminal into the working directory for the project and do the following:

#### Create and activate a virtual environment

On Windows (cmd.exe):

    $ python3 -m venv env
    $ env\Scripts\activate.bat

On Unix or MacOS (bash):

    $ python3 -m venv env
    $ source env/bin/activate

#### Install project dependencies

    $ pip install -r requirements.txt

#### Create the database

    $ python manage.py migrate

#### Create an admin user for yourself

    $ python manage.py createsuperuser

#### Start the server

      $ python manage.py runserver

If everything worked, http://127.0.0.1:8000 will show you a welcome page
