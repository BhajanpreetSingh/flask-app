# Flask Bare-Minimum Application

Simple Python + Flask web application.

## Project structure

flask-bare-minimum-app/
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
├── templates/
│   └── index.html
└── static/
    └── css/
        └── style.css

## Run locally

Create a virtual environment:

python3 -m venv venv

Activate it on Linux/macOS:

source venv/bin/activate

On Windows:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run the application:

python app.py

Open in browser:

http://localhost:5000

The Flask application listens on 0.0.0.0:5000.
