# Spam Message Detector App

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-lightblue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![NLTK](https://img.shields.io/badge/Library-NLTK-blue.svg) ![scikit-learn](https://img.shields.io/badge/Library-sklearn-orange.svg)  ![Pandas](https://img.shields.io/badge/Library-Pandas-darkblue.svg) ![Platform](https://img.shields.io/badge/Platform-Heroku_Cloud-purple.svg)

This is an AI-based spam classification system developed using Flask and deployment at Heroku Cloud.

## Technologies Used
The following technologies are used developing this web application:
- Boostrap(Frontend)
- Flask(Backend)
- Sklearn(Model Development)
- Pandas(Data Handling)
- Heroku Cloud (Hosting Server)

## Workflow
1. Importing essential libraries
2. Loading the dataset
3. Importing essential libraries for performing Natural Language Processing on 'Spam Collection' dataset
4. Cleaning the messages
	5. Cleaning special character from the message
	6. Converting the entire message into lower case
	7. Tokenizing the review by words
	8. Removing the stop words
	9. Stemming the words
	10. Joining the stemmed words
	11. Building a corpus of messages
12. Creating the TF-IDF model
13. Model Building(LogisticRegression)
14. Deploy Model in Heroku using Flask

## Screenshot
![Spam Message Detector App Screenshot](https://raw.githubusercontent.com/TechyNilesh/Spam-Message-Detector-App/master/screenshot.png "Spam Message Detector App Screenshot")

## Live WebApp Link'
https://spam-message-detector-app.herokuapp.com/


### Please do ⭐ the repository, if it helped you in anyway.
