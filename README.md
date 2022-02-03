# Sentiment-Analysis-on-Twitter-Data

The purpose of this repository is to conduct a project from data ingestion to data visualization. 
We chose to apply sentiment analysis model on our data to get to know better the users'behaviours and preferences.


This is the main Twitter Data analysis repository.

**General**

Before running the scripts, some dependencies must be installed.
To do this, you can use the following command : 

        pip install -r requirements.txt

**Content**

The repository contains many a "main" folder where we developed a few jupter notebooks in order to assure data collection and data preprocessing. 
We performed the sentiment analysis model on some cleaned tweets by getting scores and some properties (neg, neu, pos, comp) that were helpful for the analysis.

If you wish to work on a new environment, you can execute the following on your terminal:

* Install virtualenv

        pip install virtualenv

* Create virtualenv (f.e in root project directory)

        virtualenv -p python3 venv

* Activate env (you need to this every time before starting up a notebook or running python scripts)

        source venv/bin/activate
