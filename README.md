# Project Title

LiveStreaming of Twitter Data

## Getting Started

To get this running clone the repository and follow the below instructions
### Prerequisites

Install tweepy python package 
```
pip install tweepy
```

### Running the code

start the jupyter notebook and first go to dataScraping Ipython Notebook
add your Access Token and other things that you can get from Twitter Developer Platform


Change the keyword under this line
```
stream.filter(track=['#AACR20'])
```

Run this code and it will start getting Live tweets based on the keywords

## Getting the desired data from JSON file

Go to filterData Ipython Notebook and after running the code, you will get
```
Name, Date, and the full text of the tweet
```
You can get other parameters also by adjusting the code a bit

Export the data as excel or csv file based on the requirement



