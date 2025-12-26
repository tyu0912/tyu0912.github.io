---
title: "Yann LeCun's Review on Deep Learning"
date: 2019-01-14 06:58:00 -0500
categories: [AI]
tags: [learnings]
---

A great [article](https://ucb-mids.s3.amazonaws.com/prod/Machine+Learning/Readings/Week+7/DeepLearningReview.pdf) to read for deep learning. Written simply and yet packs in a lot of technical detail:

Some notes on RNN from paper:
- RNNs process an input sequence one element at a time, maintaining in their hidden units a ‘state vector’ that implicitly contains information about the history of all the past elements of the sequence
- Very good at predicting the next character in a text
- If a particular first word is chosen from this distribution and provided as input to the decoder network it will then output a probability distribution for the second word of the translation and so on until a full stop is chosen
- Although their main purpose is to learn long-term dependencies, theoretical and empirical evidence shows that it is difficult to learn to store information for very long
- Essentially, the architecture is one where the output from the hidden layers at time (t) are refead back into the exact same layer at the next iteration.