# ITI-CI-Demo

A simple Flask application with GitHub Actions CI/CD pipeline demonstration.

## Project Overview

This repository contains:
- A basic Flask web application (`app.py`)
- Unit tests for the application (`test_app.py`)
- GitHub Actions workflow for continuous integration (`.github/workflows/ci.yml`)

## Application Code

The Flask application has a single route that returns "Hello, ITI!":

```python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def home():
    return "Hello, ITI!"

if __name__ == '__main__':
    app.run()

## Github Action pipeline
<img width="1397" height="560" alt="image" src="https://github.com/user-attachments/assets/8c7623a8-d33c-485b-96fe-70947baa55aa" />

