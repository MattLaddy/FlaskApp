python -m venv <name>
source <name>\scripts\activate
pip install flask-sqlalchemy

python (in python)

from app import db
db.create_all()

pip install Flask-Migrate

flask db init
flask db migrate -m "Initial migration"
flask db upgrade

python app.py