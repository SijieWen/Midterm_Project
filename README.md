# Midterm_Project
# FE595-Midterm Project (Restaurant NLP Service)
## About:
This project is to create an NLP web service for restaurants around Hoboken, Newport, New York area. There are 6 returned services per input, they are sentimental analysis, translation service, 10 most common adj words, 10 most common noun words, top 10 positive words and top 10 negative words.
## Usage
Connect to your AWS firstly
Git clone https://github.com/SijieWen/Midterm_Project
Download yelpsearch.py and templates folder from Github, save them under same directory
Run yelpsearch.py file in your terminal correctly, using the following command lines:
```bash
export FLASK_APP=yelpsearch.py
python -m flask run
```
Copy port address (http://127.0.0.1:5000/) into browser.
Follow the instructions, input interested restaurant name and service, click submit

## Contribution
Sijie Wen:
Draft a demo of this project
Program a function to collect restaurants’ names and business ids using Yelp business fusion API, test use the Yelp Review Search API, prepare for the following steps of building our database 
Program the whole function of Flask app, adjust and arrange every member's services into this app as correct format
Write corresponding HTML files with instructions
Create NLP service – translate the reviews of a restaurant into Chinese
Create NLP service – overall rating based on the sentiment score for a restaurant
Test and debug programs and web services

Xiaolu Li:
Propose the idea and flow of the project
Program a function to collect 5 areas restaurants’ names and business ids using Yelp business fusion API. This is the database for this project 
Program a function to get input restaurant name from user, if there is a match with our database. The function will script the first page of reviews on Yelp (we didn’t use the Yelp Review Search API, because it only returns 3 reviews)
Create NLP service – most commonly used adjective words for a restaurant
Create NLP service – most commonly used noun words for a restaurant
Test and debug programs

Yamin Tang:
Create NLP service – top 10 positive noun phrases used for a restaurant
Create NLP service – top 10 negative noun phrases used for a restaurant
