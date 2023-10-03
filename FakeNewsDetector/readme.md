# Fake News Detector
In today's world articles, posts, news can be generated and spread easily. Analyzing the articles, detecting misinformation and stopping from spreading is crucial to maintaing the safety in society. Fake information can spread false information, leading people to make incorrect decisions based in inaccruate data. Fake information can impact the election results, economic, social, health and safety of people.

## Overview

This application generates different models to identify the fake news and evaluate the performance of those models. As part of this project, we are considering following methods to create the models:

Passive Aggressive Classifier
Gradient Boost Classifier
Support Vector
Extreme Gradient Boost Classifier
I also used same methods on news text and tokenized/lemmanized text to evaluate the performance of the different models.

## Conclusion

Based on all the methods, Passive aggressive classifier shows the best result based on the accuracy, followed by gradient boost and Support vector machine. Although the difference in accuracy is not much but time taken to train the model have huge difference.

Passive Aggressive classifier took few seconds to train the model, Gradient boost took in minutes whereas Support Vector took hours.

It can be noticed that if the text is tokenized and stemmed, the accuracy of the model improves. This is applicable for all the models as it reduce the unwanted text.

​

