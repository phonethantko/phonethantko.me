---
title: "Myanmar Sentiment Analysis"
date: 2019-05-15
author: "Phone Thant Ko"
tags: ["pytorch", "sentiment-analysis", "python", "vue.js", "flask", "heroku"]
description: ""
---
>A research project on Myanmar sentiment analysis using deep learning models

## Links

[Demo](https://fyp.phonethantko.me/demo) |
[Description](https://fyp.phonethantko.me) |
[Github - Backend](https://github.com/phonethantko/mmSentiment-api) |
[Github - Frontend](https://github.com/phonethantko/mmSentiment-demo)

## Summary

Sentiment analysis in text has become highly significant in obtaining useful information across social media. While there have been ample amount of research work done for English language, languages such as Myanmar remain underappreciated for this area of research. Recent years have seen a few researchers initiating the work on Myanmar language albeit limited to using lexicon-based approaches. This project proposes the Long Short-Term Memory recurrent neural network (LSTM) for classifying sentiments across Myanmar text. To our knowledge, this is the first attempt at exploring deep learning models for this task.

![Alt](/img/mmsentiment/sample.jpg)

>Testing the app loaded with the model -  the Myanmar equivalent of 'It's delicious' gives a score close to 1.0; i.e - positive sentiment

## Background

Myanmar (Burmese) script is recognized as Tibeto/Burman language group, developed from the Mon script anddescended from the Brahmi script of ancient South India.(Thompson, I. 2013) Despite the emerging NLP tools for different languages, the research done for Myanmar language has remained minimal to date.

## Results

The trained model achieved 76.5% accuracy on testing dataset, which is a satisfactory result for an empirical attempt.

## References

Thompson, I. (2013), ‘Burmese’, http://aboutworldlanguages.com/burmese.
