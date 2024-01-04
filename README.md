# Recipe App API

This is a Recipe App API built with Django and Django REST Framework.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.9
- Docker

### Installing

1. Clone the repository

```sh
git clone https://github.com/yourusername/recipe-app-api.git
```

2. Build the Docker image

```sh
docker build .
```

3. Run the Docker container

```sh
docker-compose up
```

## Running the tests

```sh
docker-compose run --rm app sh -c "python manage.py test && flake8"
```

## Built With

- [Django](https://www.djangoproject.com/) - The web framework used
- [Django REST Framework](https://www.django-rest-framework.org/) - Toolkit for building Web APIs
- [Docker](https://www.docker.com/) - Containerization platform
