Sentiment Analysis

##Overview

It uses [TFLearn](http://tflearn.org/) to train a Sentiment Analyzer on a set of IMDB [Movie ratings](https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset). Once trained, given some input text, it will be able to classify it as either positive or negative. The neural network that is built for this is a [recurrent network](https://en.wikipedia.org/wiki/Recurrent_neural_network). It uses a technique called [LSTM](http://colah.github.io/posts/2015-08-Understanding-LSTMs/).

##Dependencies

* tflearn

Use [this](http://tflearn.org/installation/) guide to install TFLearn. Or just use the Amazon Web Services prebuilt [AMI](https://aws.amazon.com/marketplace/pp/B01EYKBEQ0/ref=_ptnr_wp_blog_post) to run this in the cloud


##Usage

Run ``demo.py`` in terminal and it should start training


##Credits

Credits for this code go to the [author](https://github.com/aymericdamien) of TFLearn.
