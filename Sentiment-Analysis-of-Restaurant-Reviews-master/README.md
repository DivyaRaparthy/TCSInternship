# AUTOMATE DETECTION OF DIFFERENT SENTIMENTS FROM TEXTUAL COMMENTS AND FEEDBACK

If you want to see the final result this is the link: https://sentiment-analysis-of-reviews.herokuapp.com/


# Introduction

- Automate detection of different sentiments from textual comments and feedback, A machine learning model is created to understand the sentiments of the restaurant reviews. The problem is that the review is in a textual form and the model should understand the sentiment of the review and automate a result. 
- The main motive behind this project is to classify whether the given feedback or review in textual context is positive or negative. 
Reviews can be given to the model and it classifies the review as a negative review or a positive. This shows the satisfaction of the customer or the experience the customer has experienced.
- The basic approach was trying a different machine learning model and look for the one who is performing better on that data set. The restaurant reviews are very related to the project topic as reviews are made on websites and we can apply this model on such data sets to get the sentiments.

# 2. Problem Definition and Algorithm

### 2.1 Task Definition

> To develop a machine learning model to detect different types of sentiments contained in a collection of English sentences or a large paragraph.

I have chosen Restaurant reviews as my topic. Thus, the objective of the model is to correctly identify the sentiments of the users by reviews which is an English paragraph and the result will be in positive or negative only.

For example, 

If the review given by the user is:
> “ We had lunch here a few times while on the island visiting family and friends. The servers here are just wonderful and have great memories it seems. We sat on the oceanfront patio and enjoyed the view with our delicious wine and lunch. Must try! ”

Then the model should detect that this is a positive review. Thus the output for this text will be **Positive**.

# 4. Work

* The approach was straight forward. I have selected a few classifiers algorithms for my project. I chose restaurant reviews as my project title. Firstly I understood the working of the algorithm and read about them.

* After gathering the data set from Kaggle. The first step was to process the data. In data processing, I used NLTK (Natural Language Toolkit) and cleared the unwanted words in my vector. I accepted only alphabets and converted it into lower case and split it in a list.
Using the PorterStemmer method stem I shorten the lookup and Normalized the sentences.
Then stored those words which are not a stopword or any English punctuation. 
* The best model was tuned to get a better result.

* Lastly, we checked the model with real reviews and found the model is detecting the sentiments of the customer reviews properly.

* Google Colab Notebook [here](https://colab.research.google.com/drive/1kblB-lavQTm9eRWlGQMwdKLKnE8hUymW?usp=sharing).


# 7. Conclusion

The motive of the model is to correctly detect the sentiments of the textual reviews or feedback. The developed model has an accuracy of 77.67% and successfully detects the sentiments of the textual reviews or feedback.
The model has been tested with few of the online reviews and was found that it detects the sentiments correctly.
Thus, can conclude that the motive was successful and the model can be used to detect the sentiments of the reviews and feedback.

