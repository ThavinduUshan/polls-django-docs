# Django Polls App

This repository contains the source code for a Polls app developed following the Django documentation tutorial.

## Tutorial Parts Covered:

1. [Part 1: Requests and responses](https://docs.djangoproject.com/en/stable/intro/tutorial01/)
2. [Part 2: Models and the admin site](https://docs.djangoproject.com/en/stable/intro/tutorial02/)
3. [Part 3: Views and templates](https://docs.djangoproject.com/en/stable/intro/tutorial03/)
4. [Part 4: Forms and generic views](https://docs.djangoproject.com/en/stable/intro/tutorial04/)
5. [Part 5: Testing](https://docs.djangoproject.com/en/stable/intro/tutorial05/)
6. [Part 6: Static files](https://docs.djangoproject.com/en/stable/intro/tutorial06/)
7. [Part 7: Customizing the admin site](https://docs.djangoproject.com/en/stable/intro/tutorial07/)
8. [Part 8: Adding third-party packages](https://docs.djangoproject.com/en/stable/intro/tutorial08/)

## Description

This Polls app allows users to create, view, and vote on polls. It includes functionality for creating questions with multiple choices and displaying the results of those polls.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/polls-app.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run migrations:

```bash
python manage.py migrate
```

4. Create a superuser:

```bash
python manage.py createsuperuser
```

5. Start the development server:

```bash
python manage.py runserver
```

6. Access the admin site at `http://localhost:8000/admin/` and create some polls and choices.

7. Visit the Polls app at `http://localhost:8000/polls/` to view and vote on polls.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.