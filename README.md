# Naive bayes algorithm

This README outlines the details of naive bayes algorithm in machine learning

## Prerequisites

You will need the following things properly installed on your computer.

* [python3.6](https://www.python.org/downloads/)
* numpy
* matplotlib 
* pandas
* dataset 

or you can use google colab notebook
* https://colab.research.google.com

## Explanation
A classifier is a way to use math to identify something. For example, you see something on the playground that is red. It could be a playground ball, or maybe a rabbit, or a tennis ball - but it's probably not a rabbit or tennis ball because you've never seen a red one of those before.

A Bayes Classifer is, then, something that uses Bayes rules to figure out how often red things are playground balls, how often they are rabbits, and how often they are tennis balls and then picks the one that happens most often. If most playground balls are red, and most rabbits an tennis balls are not, then when you see something that's red, it's probably a playground ball.

A Naive Bayes Classifier is one where you have several things that describe what you are looking at, like it's color, size, whether it has eyes or not… and you assume that they have nothing to do with each other. The color of something has nothing to do with it's size or whether it has eyes or not. This might not be a good a assumption, for example, there are very few purple things with eyes. But we may not know that, so we'll just say that it is so because it makes the math much easier.
