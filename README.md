leaguetool
=========

A league of legends tool.

Packages used
=========

Before installing the necessary packages, I created a virtual environment using the following command:

python -m venv flask

These commands were then used to install the needed packages for this program. From the microblog-version-0.4 directory, use pip to install each of the following:

flask\Scripts\pip install flask

flask\Scripts\pip install flask-mail

flask\Scripts\pip install flask-sqlalchemy

flask\Scripts\pip install sqlalchemy-migrate

flask\Scripts\pip install flask-whooshalchemy

flask\Scripts\pip install flask-wtf

flask\Scripts\pip install flask-babel

flask\Scripts\pip install guess_language

flask\Scripts\pip install flipflop

flask\Scripts\pip install coverage

flask\Scripts\pip install requests

How to run
=========

To run this program, I used the following command from the microblog-version-0.4 directory:
flask\Scripts\python application.py
Then proceed to the local page with the correct port (default 5000).

NOTE
=========

In the app/views.py file, the database commands to add users u and k have been commented out, since it only needs to be done once to get the users in the database. On first run will need to uncomment these lines, then comment them out/delete them for future use or program will crash because those unique players were already added.
