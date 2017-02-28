**Boilerplate Generating Script**

This script installs commonly used Flask extensions and creates a simple directory structure for Flask apps. You can add other files as you see fit by editing `generate_boiler_plate`. Functionality will be added as needs dictate :-)

The directory structure will look as follows:

.
+-- app.py
+-- config.py
+-- __init__.py
+-- main.py
+-- models.py
+-- requirements.txt
+-- scripts
    +-- create_db.py
+-- static
    +-- css
    +-- img
    +--js
+-- templates
    +-- base.html
    +-- home.html
    +-- login.html
    +-- register.html
+-- views.py

**Getting up and running**

**Assumption** - [`virtualenv`](http://docs.python-guide.org/en/latest/dev/virtualenvs/) is installed.

It is _highly_ recommended you install the [Anaconda Python Distribution](https://www.continuum.io/downloads)

- Clone the repo.
- Change the repo name to your project's name.
- Open `generate_boiler_plate`.
- Change `venv` to a name you prefer for your virtual environment. You can also edit the file and add your preferred configurations. Otherwise, it works fine for small apps. Also, feel free to make any changes to the script that you see fit.
- Run `chmod +x generate_boiler_plate`, then `./generate_boiler_plate`.

_The script deletes itself and README.md once it has executed._
