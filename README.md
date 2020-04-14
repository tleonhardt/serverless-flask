# Serverless Flask Application

This is code which follows the tutorial 
[Build a Python REST API with Serverless, Lambda, and DynamoDB](https://serverless.com/blog/flask-python-rest-api-serverless-lambda-dynamodb/) 
to create a deploy a serverless REST API using [Serverless Framework](https://github.com/serverless/serverless) and 
[Flask](https://flask.palletsprojects.com).

## Prerequisites

### JavaScript

```shell script
npm install
```

### Python

```shell script
pipenv install
pipenv shell
```

## Run Flask App locally

```shell script
pipenv shell
python app.py
```

## Deploy to AWS

```shell script
sls deploy
```
