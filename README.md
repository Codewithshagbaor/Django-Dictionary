# Django Dictionary

This is a simple dictionary application built using Django and PyDictionary. It allows users to search for the meanings of words, as well as their synonyms and antonyms.

## Features
- Search for the meanings, synonyms and antonyms of words
## Later Feature
- Save words and view them later
- User authentication and registration
- Admin panel to manage words

## Requirements
- Python 3
- Django 3
- PyDictionary
- Pillow (for image handling)

## Installation
1. Clone the repository
```
git clone https://github.com/Codewithshagbaor/Django-Dictionary.git
```
then

2. Install the requirements
```
pip install -r requirements.txt
```
3. Run migrations
```
python manage.py makemigrations
python manage.py migrate
```
4. Run the server
```
python manage.py runserver
```
6. Access the application by visiting http://localhost:8000/ in your browser

## Usage
1. Search for words by visiting http://localhost:8000/
2. Register or login to save words and view them later
3. Use the admin panel to manage words by visiting http://localhost:8000/admin/

## Contributions
This project is open to contributions. If you find any bugs or have any suggestions, feel free to open an issue or a pull request.
