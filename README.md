# NLP All in One
A complete NLP guideline with code. This project covers all the main steps required to complete NLP projects. The pipeline include EDA, data cleaning, modeling, results interpretation. The data is taken from a Kaggle competition named [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started) where the goal to predict if a tweet is about any disasterous situation or not. This data is selected as it contains different type of variables like text, categorical, geographical etc. The EDA contains various visualizations and since github do not display all of these plots, so these plot are being displayed using the saved images for the display purposes. The original plots and maps are interactive.

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
- Modeling using FastText classifier
- Threshold search for improved results
- Model results explainability with LIME


## Credits and Downloads:
- Data is taken from [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started/overview) Kaggle competition. Download data [here](https://www.kaggle.com/c/nlp-getting-started/data). 
- Download 300d GloVe embeddings [here](https://www.kaggle.com/authman/pickled-glove840b300d-for-10sec-loading). 
