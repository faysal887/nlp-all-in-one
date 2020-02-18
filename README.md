# NLP All in One
A complete NLP guideline with code. This project covers all the main steps of nlp projects pipeline including EDA, data cleaning, modeling, results interpretation. The data is taken from a Kaggle competition named where we had to predicted if a tweet is about any disasterous situation or not. This data is selected it contains different type of variables like text, categorical, geographical etc. The EDA contains various visualizations and since github do not display all the plots so I have display the saved images of these plots for the display purpose. 

## Setup
- Install all dependencies
- Download data
- Download GloVe vectors

## Functionalities Covered
- Initial EDA with pandas-profiling
- Target variable distribution visualization
- Categorical variable(s) distribution
- Word clouds for train, test dataset
- Visualize text data in 2D using glove and tfidf
- Check embeddings coverage for our corpus
- Interactive plots for geo-graphical features
- N-gram plots
- Spell correction
- Extracting meta features e.g. num of words, num of punctuations, num of numerals per class
- Extracting readability features
- Sentiment analysis using Allen-NLP
- Modeling using FastText and Logistic regression model
- Threshold search for improved results
- Model results explainability with LIME


## Credits and Downloads:
- Data is taken from [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started/overview) Kaggle competition. Download data [here](https://www.kaggle.com/c/nlp-getting-started/data). 
- Download 300d GloVe embeddings [here](https://www.kaggle.com/authman/pickled-glove840b300d-for-10sec-loading). 
