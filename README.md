
### How to Start a Project:

Clone the repository and open it in the command-line interface:

```
git clone https://github.com/nebius-academy-templates/python-flask-movie-review-precode.git
```

```
cd python-flask-movie-review-precode
```

Create and activate a virtual environment:

```
python3 -m venv venv
```

```
source venv/bin/activate
```
On Windows

```
source env/Scripts/activate
```

Install the dependencies from the requirements.txt file:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Add values to env variables in .env:

```
FLASK_APP=
FLASK_DEBUG=
DATABASE_URI=
SECRET_KEY=
```

Create and apply migrations, then run the project:

```
flask run
```
