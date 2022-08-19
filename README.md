# Tweet-Analyzer

Web App Link : https://shre11-tw-app-zmodmk.streamlitapp.com/


Images:
![image](https://user-images.githubusercontent.com/56075324/185561540-15e4beab-461e-44ed-9d80-d1ea84df7056.png)
![image](https://user-images.githubusercontent.com/56075324/185561726-3afc9a83-4daf-4bec-a72e-95f5b97fb5bd.png)
![image](https://user-images.githubusercontent.com/56075324/185561821-7ea4e479-db61-4299-a432-3983ecbf5535.png)

This is a twitter integrated web application that takes a twitter handel as input and does:

1. Analyze the tweets of your favorite celebrities

This tool performs the following tasks:

Retrieves the 5 most recent tweets from the given twitter handle
Generates a Word Cloud
Performs sentiment analysis and displays it in the form of a bar chart
2. This tool retrieves the last 100 tweets from a twitter handle and performs the following tasks Converts it to a DataFrame

Clears the text

It analyzes the subjectivity of tweets and adds another column to the table. 
It also analyzes the polarity of tweets and adds another column to the table and it analyzes the sentiments of tweets and adds another column to the table.
This repository contains all the files for end-to-end model building and deployment of the tweet analyzer web application

Tweet_Analyzer.ipynb : Model build file

Twitter Data : File created after each query in the web application

Requirements.txt: Requirements file

setup.sh : predefined file for streamlite on heroku
This app is created on a tool called Streamlit which saves you from the headache of front-end devlopment ,you can install it by:
Streamlit documentation: https://docs.streamlit.io/en/latest/

pip install streamlit

& to run it on local host : streamlit run myfile.py
