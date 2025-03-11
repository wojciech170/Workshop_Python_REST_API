# Workshop: Python REST API

A project developed as part of a workshop focused on designing and implementing a backend using Django REST Framework (DRF). The application manages a cinema system, allowing users to interact with movies, cinemas, and screenings through a RESTful API.

## Project Status 
This project is in the early stages of development. Work is ongoing to establish the basic structure and implement initial features. Stay tuned for updates in the repository!

## Features

### Existing Endpoints:
- `/movies/` - `GET`: Retrieve a list of movies, `POST`: Add a new movie
- `/movies/{id}/` - `GET`: Retrieve movie details, `PUT`: Update movie, `DELETE`: Remove movie

### New Endpoints:
- `/cinemas/` - `GET`: Retrieve a list of cinemas, `POST`: Add a new cinema
- `/cinemas/{id}/` - `GET`: Retrieve cinema details, `PUT`: Update cinema, `DELETE`: Remove cinema
- `/screenings/` - `GET`: Retrieve a list of screenings, `POST`: Add a new screening
- `/screenings/{id}/` - `GET`: Retrieve screening details, `PUT`: Update screening, `DELETE`: Remove screening

## Technologies Used
- Python
- Django REST Framework
- PostgreSQL (or SQLite for development)
- Docker (optional for containerized deployment)
- Pytest / Unittest for testing

## Installation

### 1. Clone the repository
```sh
git clone https://github.com/wojciech170/Workshop_Python_REST_API.git
cd Workshop_Python_REST_API
```
### 2. Create and activate a virtual environment
```
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```
### 3. Install dependencies
```
pip install -r requirements.txt
```
### 4. Apply migrations
```
python manage.py migrate
```
5. Run the development server
```
python manage.py runserver
```
The API will be available at http://127.0.0.1:8000/.

## Running Tests
To run tests, use:

```
pytest
```
or
```
python manage.py test
```
