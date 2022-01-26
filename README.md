# Example Project (FastAPI)

Updated: 2022-01-26

## Overview

A static simple website ready to deploy.
This repo includes all the file and it is ready to deploy to Heroku.

## Requirement

See requirements.txt for updates.

## Installation & Usage

```bash
$ git clone https://github.com/imanojkumar/ML_Deployment_Project1.git
$ cd ML_Deployment_Project1
# install packages
$ pip install -r requirements.txt
# start the server
$ uvicorn app.main:app --reload --port 8000
```

Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/).


## Features

- Menu
- Markdown pages

## Test

```bash
# Change the directory
$ cd ML_Deployment_Project1
# Run tests
$ pytest -v
```
