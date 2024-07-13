# Basic Web Application

This is a basic web application that allows users to input data, validate it, store it in a database, retrieve it, and display it in a table format.

## Setup and Run

1. Create a new environment:
    ```bash
    conda create -n webapp python=3.8
    conda activate webapp
    ```

2. Install required packages:
    ```bash
    conda install flask sqlalchemy flask-wtf wtforms
    ```

3. Run the application:
    ```bash
    python app.py
    ```

4. Access the application at:
    ```
    http://127.0.0.1:5000
    ```

## Features

- User Input Form with fields for Name, Email, Age, and Date of Birth.
- Client-side validation for email format and positive integer for age.
- Data storage in an SQLite database.
- Data retrieval and display in a tabular format.
