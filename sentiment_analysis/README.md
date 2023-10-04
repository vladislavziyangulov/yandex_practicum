# Toxic comment detection

A dataset of different comments classified into toxic and neutral is preprocessed, analysed and TF-IDF vectorized. 
A model is built to help with the detection of toxic comments that will be sent to moderation

# Brief summarizon

Words typical of toxic and non-toxic comments are illustrated using a word cloud.

In total there are over 10,000,000 words, of which about 177,000 words are unique.

Some words are unique to and commonly used in toxic comments. 
There are over 8,000 such words in the dataset and in total they were used more than 24,000 times. 

Toxic comments often contain exclamation points. 

The pronoun "you" is used 2.5 times more often in negative comments. 
(Perhaps, neutral comments use "I-statements" more often and do not, unlike toxic comments, use ad hominem attacks involving pronoun "you")

Although the model is overfitted, its f1-measure is acceptable

# Used libraries/tools

nltk, re, TF-IDF vectorizer

worldcloud, collections

sklearn, LGBM
