Greetings,

I have used Google Colab for the coursework and the dataset are uploaded to google colab. Please upload the 
"CSC8111 - Machine Learning Coursework" folder to your google drive. From there you can open the file in the colab to check the work.

Thank you and Happy Coding !!!
_____________________________________________________________________________________________________________________________________________

Question 1:
-----------

Description and requirements for the tabular dataset.

The dataset, called FARS, is a collection of statistics of US road traffic accidents. The class label is about the severity of the accident. 
It has 20 features and over 100K examples. The dataset is available through several repositories of machine learning benchmarks, and can be 
loaded easily within a python program, after installing the pbml library (pip install pbml):

from pmlb import fetch_data
X,y = fetch_data('fars',return_X_y=True)

X will contain the matrix of input features, and y will contain the class labels.

Experiments on the tabular dataset will be relatively fast compared to the other three options. To compensate, we expect that you evaluate a 
very broad range of options for the design of your machine learning pipelines, including (but not limited to) data normalisation, 
feature/instance selection, class imbalance correction, several (appropriate) machine learning models, hyperparameter tuning and 
cross-validation evaluation.
_____________________________________________________________________________________________________________________________________________

Question 3:
-----------

Description and Requirements for the text dataset.

Dataset: sentiment analysis dataset.

(on canvas: Tweets_train.csv, https://ncl.instructure.com/courses/48554/files/6271480?wrap=1, 
Tweets_dev.csv, https://ncl.instructure.com/courses/48554/files/6271483?wrap=1, 
Tweets_test.csv, https://ncl.instructure.com/courses/48554/files/6271533?wrap=1). 

Each sample in the dataset represents a tweet. Each tweet has a sentiment label (Positive, Negative, Neutral).

Task Description: Apply a combination of different approaches including pre-processing techniques, shallow and deep classifiers, 
ensembled approaches, machine learning approaches beyond supervised learning if applicable, data augmentation if applicable to 
predict the sentiment of the test set. Try your best to improve the prediction results.

Evaluation metrics: F-1 measure.
_____________________________________________________________________________________________________________________________________________

