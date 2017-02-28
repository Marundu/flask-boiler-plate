**Boilerplate Generating Script**

This script installs commonly used Flask extensions and creates a simple directory structure for Flask apps. You can add other files as you see fit by editing `generate_boiler_plate`. Functionality will be added as needs dictate :-)

The director structure will look like the image in the Wiki (does not show the `venv` folder).

![Here is a screenshot of the directory structure:]
(https://github.com/Marundu/flask-boiler-plate/blob/master/flask_boiler_plate_tree_output.png|alt=dir_structure)

**Getting up and running**

**Assumption** - [`virtualenv`](http://docs.python-guide.org/en/latest/dev/virtualenvs/) is installed.

It is _highly_ recommended you install the [Anaconda Python Distribution](https://www.continuum.io/downloads)

- Clone the repo.
- Change the repo name to your project's name.
- Open `generate_boiler_plate`.
- Change `venv` to a name you prefer for your virtual environment. You can also edit the file and add your preferred configurations. Otherwise, it works fine for small apps. Also, feel free to make any changes to the script that you see fit.
- Run `chmod +x generate_boiler_plate`, then `./generate_boiler_plate`.

_The script deletes itself and README.md once it has executed._
