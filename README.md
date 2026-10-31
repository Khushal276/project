
# Accounts Service

![Build Status](https://github.com/Khushal276/project/actions/workflows/ci-build.yaml/badge.svg)

## Project Overview

The Accounts Service is a REST API built with Flask for managing customer accounts. It supports creating, reading, updating, deleting and listing accounts.

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
