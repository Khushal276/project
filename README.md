
# DevOps Capstone
![Build Status](https://github.com/Khushal276/project/actions/workflows/ci-build.yaml/badge.svg)

DevOps Capstone is a REST API accounts service built with Flask. It uses GitHub Actions for continuous integration (linting and unit tests) and is deployed with Docker, Kubernetes and a Tekton CD pipeline.

## Project Overview


## Features

- RESTful CRUD endpoints for accounts
- Continuous integration with GitHub Actions
- Automated linting using Flake8
- Unit testing using Nose
- Containerized with Docker
- Deployed on Kubernetes
- Automated CD pipeline with Tekton

## Running the Tests

Install dependencies:

    pip install -r requirements.txt

Run tests:

    nosetests
