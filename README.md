# Task

This project contains a Python script that fetches user data from a public API and prints selected details. It demonstrates using the GET method, JSON handling, loops, and basic error handling.

## API Used
https://jsonplaceholder.typicode.com/users

The script displays the following fields for each user:
- Name
- Username
- Email
- City

It also includes a condition to print only users whose city name starts with the letter "S".

## Requirements
- Python 3.8 or later
- requests library

Install the dependency:
pip install requests

## How to Run
python fetch_users.py

The script will fetch users from the API and print only those whose city begins with “S”.

## Error Handling
The script safely handles:
- Network errors
- Timeout errors
- Invalid or non-JSON responses
- Failed HTTP responses

## Files Included
- fetch_users.py
- README.md
