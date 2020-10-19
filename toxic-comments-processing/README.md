### Comments classification model for an online store

**Description of the project:** An online store is launching a new service. Users can now edit and add product descriptions just like in wiki-community.
The goal is to create a tool that searches for toxic comments and submit them for moderation. We'll train the model to classify comments into positive and negative. 

The value of the quality metric F1 for the model must be at least 0.75.

**Result:** The model was built and trained. The value of the metric F1 has reached the required value. Feature engineering is applied to texts and time series.
Texts were vectorized using word2vec.

**Tools and techniques:** Pandas, sklearn, numpy, NLTK, LightGBM, CatBoost, ML, cross-validation, stemming, feature engineering, word2vec, R

**Project status:** Completed
