
# Fandango F360 Admin Report Generator

# Description

This Utility creates an excel report Account wise for each Studio.</br>

## Technologies

Language
------------
Python

## Running the Utility Locally

### Run the below command to install the required dependencies

```pip install -r requirements.txt```

If you have issues installing dotenv on a virtual env remove dotenv from requirements.txt file and run ```pip3 install python-dotenv``` or 
```pip install python-dotenv```

### Create .env file

Create a .env file in the root directory with the below variables.

``` shell
USER_NAME="<YOUR_DB_LOGIN_ID>"
PASSWORD="<YOUR_DB_LOGIN_PWD"
HOST_NAME="<YOUR_DB_HOST_NAME>"
PORT="5432"
DB="<DB_NAME>"
DB_SCHEMA="f360"
```
### Run the Utility with the below command

```python report-generator.py```

<b> OR </b>

```python3 report-generator.py```
