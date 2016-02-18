Python TravisCI Deploys
======

Testing out TravisCI deployments.

Development
------

To setup your virtualenv:

    $ mkvirtualenv myflaskapp
    $ setvirtualenvproject myflaskapp path_to_project

    # Optionally, create a new project with
    $ mkproject myflaskapp
    $ git clone git@github.com:jsvgoncalves/flask-starter-guide .

Then, everytime you work on the project, run:

    $ workon myflaskapp

To install the dependecies run:

    $ pip install -r requirements.txt

### Virtualenvwrapper cheatsheet

    # To stop working
    $ deactivate
    # To show all environments
    $ workon
    # To show installed packages
    $ lssitepackages
