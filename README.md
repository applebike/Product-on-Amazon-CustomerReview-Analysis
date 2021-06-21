# Product-on-Amazon-CustomerReview-Analysis (NLP)
Natural Language Processing project for Amazon customer reviews

data explaination: http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/
reviews_Toys_and_Games_5.json.gz
![image](https://user-images.githubusercontent.com/73352684/122755887-44057f80-d25b-11eb-98ec-7fd53e30c4a8.png)
 


### Data Loading, Transformation and Feature Extraction:
• Loaded and transformed raw Amazon json data(1.8 GB) on EC2, including data cleaning, tokenization, removing stop words, stemming and lemmatization, converting reviews to tf-idf vector space, defining the label as the user ratings 
### Modeling and Data Product:
• Implemented and trained SVM model and two lexicon-based model(AFINN, VADER) for sentiment analysis to predict a user would like a product or not, finally achieved prediction accuracy over 90%.

• Implement topic modeling via Latent Dirichlet Allocation on both positive reviews and negative reviews. Visualize topics in a text corpus.
