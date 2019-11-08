# Midterm_Project
# FE595-Midterm Project (Restaurant NLP Service)
## About:
This project is to create an NLP web service for restaurants around Hoboken, Newport, New York area. There are 6 returned services per input, they are sentimental analysis, translation service, 10 most common adj words, 10 most common noun words, top 10 positive words and top 10 negative words.
## Usage
1. Connect to your AWS firstly

2. Git clone https://github.com/SijieWen/Midterm_Project

3. Download yelpsearch.py and templates folder from Github, save them under same directory

4. Run yelpsearch.py file in your terminal correctly, using the following command lines:
```bash
export FLASK_APP=yelpsearch.py
python -m flask run
```

5. Copy port address (http://127.0.0.1:5000/) into browser.

6. Follow the instructions, input interested restaurant name and service, click submit

## Contribution
Sijie Wen:

1. Draft a demo of this project

2. Program a function to collect restaurants’ names and business ids using Yelp business fusion API, test use the Yelp Review Search API, prepare for the following steps of building our database 

3. Program the whole function of Flask app, adjust and arrange every member's services into this app as correct format
Write corresponding HTML files with instructions

4. Create NLP service – translate the reviews of a restaurant into Chinese

5. Create NLP service – overall rating based on the sentiment score for a restaurant

6. Test and debug programs and web services


Xiaolu Li:

1. Propose the idea and flow of the project

2. Program a function to collect 5 areas restaurants’ names and business ids using Yelp business fusion API. This is the database for this project 

3. Program a function to get input restaurant name from user, if there is a match with our database. The function will script the first page of reviews on Yelp (we didn’t use the Yelp Review Search API, because it only returns 3 reviews)

4. Create NLP service – most commonly used adjective words for a restaurant

5. Create NLP service – most commonly used noun words for a restaurant

6. Test and debug programs


Yamin Tang:

1. Create NLP service – top 10 positive noun phrases used for a restaurant

2. Create NLP service – top 10 negative noun phrases used for a restaurant
