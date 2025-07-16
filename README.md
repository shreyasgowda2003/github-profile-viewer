# github-profile-viewer

A Flask-based web application that allows users to view, compare, and download GitHub profile information. Built using Python, HTML, CSS, and Flask, this tool leverages the **GitHub API** to fetch and display public data.

## Features
-  View GitHub user profiles by entering a username
-  Compare two GitHub profiles side-by-side
-  Download GitHub user bio as a '.csv' file
-  Displays avatar, name, bio, public repos, followers, following, etc.
-  Simple, responsive frontend using HTML and CSS

## Tech Stack
- Backend: Python, Flask
- Frontend: HTML, CSS
- API: GitHub REST API v3
- Data Export: CSV (via Python `csv` module)
- Tools: VS Code, Flask Dev Server

## Create and activate a virtual environment (optional but recommended)
# On Windows
venv\Scripts\activate
pip install -r requirements.txt
python app.py

github-profile-viewer/
│
├── app.py                  # Main Flask application
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
│
├── templates/
│   ├── index.html          # Main input form
│   ├── profile.html        # Profile display
│   └── compare.html        # Comparison page
│
├── static/
│   └── style.css           # Custom styling
