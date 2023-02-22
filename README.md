// Setting the environment variable FLASK_APP to the value main.py.

// Installing the dependencies for the project.
pip3 install -r requirements.txt

// Setting the environment variable FLASK_ENV to the value development.
var ambiente = "desarrollo";

export FLASK_APP=main.py
export FLASK_ENV=development
flask run --debugger --reload
