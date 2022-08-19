# Tweet-Analyzer

Web App Link : https://tweet-analyzer-tool.herokuapp.com/

This is a Web app integrated with twitter which takes the twitter handel as as input and does :

1.Analyze the tweets of your favourite Personalities

This tool performs the following tasks :
1. Fetches the 5 most recent tweets from the given twitter handel
2. Generates a Word Cloud
3. Performs Sentiment Analysis a displays it in form of a Bar Graph

2.This tool fetches the last 100 tweets from the twitter handel & Performs the following tasks
Converts it into a DataFrame

Cleans the text
1. Analyzes Subjectivity of tweets and adds an additional column for it
2. Analyzes Polarity of tweets and adds an additional column for it
3. Analyzes Sentiments of tweets and adds an additional column for it

Images:
![image](https://user-images.githubusercontent.com/56075324/185561540-15e4beab-461e-44ed-9d80-d1ea84df7056.png)
![image](https://user-images.githubusercontent.com/56075324/185561726-3afc9a83-4daf-4bec-a72e-95f5b97fb5bd.png)
![image](https://user-images.githubusercontent.com/56075324/185561821-7ea4e479-db61-4299-a432-3983ecbf5535.png)



This respository contains all the files for end to end model building and deployment of tweet analyzer web app

Procfile : To generate command to run the app

Tweet_Analyzer.ipynb : Model building File

Twitter Data : File created after every query on the web app

Requirements.txt: Requirement file

setup.sh : predefined file for streamlite on heroku

This app is created on a tool called Streamlit which saves you from the headache of front-end devlopment ,you can install it by:
Streamlit documentation: https://docs.streamlit.io/en/latest/

pip install streamlit

& to run it on local host : streamlit run myfile.py
