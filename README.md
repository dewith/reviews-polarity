<!-- Add banner here -->
![Banner](/images/header.png)

# Polarity prediction using Deep Learning 😡😊

<!-- Add buttons here -->
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dewith/reviews-polarity/HEAD?filepath=P4_polarity.ipynb)
![GitHub last commit](https://img.shields.io/github/last-commit/dewith/amazon-ratings)
![GitHub](https://img.shields.io/github/license/dewith/amazon-ratings)


This project's aim is to predict the polarity using the users reviews in the spanish Amazon Review Corpus. The previous project with the EDA and ML modelling to the same data can be found [**here**](https://github.com/dewith/amazon-ratings)

**-> Project status:** [ Completed ]

<br>

## Table of contents
- [Table of contents](#table-of-contents)
- [Project description](#project-description)
    - [Methods used](#methods-used)
    - [Technologies](#technologies)
- [Results](#results)
- [Next steps](#next-steps)
- [Contact](#contact)

<br>

# Project description
[(Back to top)](#table-of-contents)

The importance of customer satisfaction is that it helps us to know the likelihood of a customer making a purchase in the future. Asking customers to rate the degree of satisfaction is a good way to see if they will become regular customers or even brand advocates.

In the present project we will try to improve the accuracy obtained in the previous project, in which some traditional machine learning techniques were tested. However, the literature points out that some neural network architectures work very well for natural language processing. Therefore the following **hypothesis** is raised: 

> Will a neural network wiht LSTM architecture improve the accuracy against a Linear SVC model with the current data?

## Methods used
* Corpus preprocessing 
* Feature engineering 
* Sentiment Analysis 
* Machine learning
* Deep Learning

## Technologies 
* Python
* Numpy, Pandas, Scipy
* NLTK 
* Matplotlib, Seaborn 
* Scikit Learn
* Keras, Tensorflow 



<br>

# Results
[(Back to top)](#table-of-contents)

The LSTM neural network produced an improvement of 0.002 in the training set and almost 0 in the validation set. The neural network slightly worsens the accuracy of negative reviews, while at the same time it slightly improves on positive ones. One could say that it predicts the classes slightly better in general, but the difference is so low that it could easily be changed by adjusting hyperparameters in both models.

In short, the hypothesis raised at the beginning of the project is rejected. Using a neural network LSTM does not improve the accuracy against an SVM algorithm with linear function.

![Results](/images/comparison.png)

It should be noted that in both models the overfit to the data was very well controlled since the accuracy in train and test does not differ much. And that is why both models are viable options to solve the problem, but the author's opinion is that the Linear SVC model has some superiority for its simplicity and interpretability.


<br>

# Next steps
[(Back to top)](#table-of-contents)

The Neural Network still has room for improvement: it is possible to test pre-trained models, make a more exhaustive exploration of hyperparameters or use corpus-trained embeddings in Spanish.

Another option to improve the current project would be include the data about the category of the product or its price. 

<br>


# Contact
[(Back to top)](#table-of-contents)

You can visit my [**Personal Website**](https://dewith.co/), follow me on [**Twitter**](https://twitter.com/DewithMiramon/), connect with me on [**LinkedIn**](https://linkedin.com/in/dewithm/), or check out the rest of my projects on my [**GitHub**](https://github.com/dewith/).

<br>
<br>

![Footer](/images/footer.png)
