# NLP-Sentiment-Analysis-of-Financial-News

It is important to find the sentiment of each news. The sentiment value gives us a better understanding whether the news was a positive, negative, mixed or neutral one. This also helps in sorting out the neutral news. News of announcements and political parties have little role to play in building the model for forecasting. Hence these can be ignored. 

* Sentiment analysis using classifiers present in scipy library of python. This classifiers should be trained on a dataset.
  Followed by testing the prediction. The prediction accuracy of the model was around 70% on an average. Click [here](https://github.com/Sabertoothtech/NLP-Sentiment-Analysis-of-Financial-News/tree/master/MovieReviewsSentimentAnalysis) for the code.

* Sentiment analysis using the Amazon Web Services Comprehend API can be found [here](https://github.com/Sabertoothtech/NLP-Sentiment-Analysis-of-Financial-News/tree/master/Sentiment%20using%20AWS%20comprehend).

* Sentiment Analysis using Nltk's Sentiment Intensity Analyser. The Sentiment intensity analyser predicts the sentiment in 4 parts positive, negative, neutral and compound. The result of this library was quite accurate and up to mark. This library is already trained library, so it helped us labeling the text with a sentiment value. Click [here](https://github.com/Sabertoothtech/NLP-Sentiment-Analysis-of-Financial-News/tree/master/MovieReviewsSentimentAnalysis) for the code.

* Sentiment Analysis using deeplearning model. The deep learning model requires a well labeled dataset in csv format. So first we need to get a labeled dataset (text with a sentiment label) and then train the model using that dataset and after training we can enter text in model and we can get a sentiment value of the text. Click [here](https://github.com/Sabertoothtech/NLP-Sentiment-Analysis-of-Financial-News/tree/master/deeplearningModel) for the code.

The accuracy of the deeplearning model is **97%**!
