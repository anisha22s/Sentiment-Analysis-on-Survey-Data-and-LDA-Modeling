
# *Sentiment Analysis on Survey Data and LDA Modeling*

## *Overview*

This project aims to analyze the sentiment and emotions of the reviews from a survey conducted at the Mondavi Center. 
The first part of the project is the exact duplicaate of code provided in the repository "Automating-Data-Workflow-Mailchimp".
This first part is essentially extracting the survey data from the Mailchimp account using API's and formatting it into a desired dataframe.
Next the code also connects to the customer data from Mailchimp and integrates the two. 

The NLP analysis starts from Row 168.
The analysis was carried out in two parts. In the first part, I performed sentiment analysis and emotion labeling on the reviews using the TextBlob and EmoRoBERTa models, respectively. The second part involved topic modeling using Latent Dirichlet Allocation (LDA) on the positive reviews. The analysis aimed to uncover the topics that are most commonly mentioned in the positive reviews.  
Further, using the wordcloud and matplotlib library, I have visualized the outputs in the form of wordclouds and bar charts.  
Due to privaxy reasons, I am not able to display the outputs but this code can be reproduced for any text data.

## *Installation*

To run this project, you will need to install the following Python packages:

nltk  
textblob  
neattext    
scikit-plot  
transformers  
pandas  
gensim  
wordcloud  
matplotlib  

## *Usage*

To use this project, follow these steps:

Clone the repository to your local machine. 
Open the Jupyter notebook and run the code  
The sentiment analysis and emotion labeling results are stored in two new columns in the original DataFrame. The LDA modeling results are displayed as tables and word clouds in the notebook.

## *Credits*

This project was created by entirely by Anisha. The sentiment analysis was performed using the TextBlob and EmoRoBERTa models. The LDA modeling was performed using the Gensim library.

