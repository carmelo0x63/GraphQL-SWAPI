# GraphQL-SWAPI
A GraphQL wrapper to a REST API (SWAPI)

mkdir GraphQL-SWAPI
cd GraphQL-SWAPI
python3 -m venv .
source bin/activate
mkdir api
vi api/__init__.py
vi main.py
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install flask flask-sqlalchemy ariadne

export FLASK_APP=main && export FLASK_ENV=development
flask run --host=0.0.0.0
