---
title: "Odd-One-Out Image Groups"
collection: publications
category: school
permalink: /publication/2026-5-03-odd-one-out
excerpt: 'We address a novel outlier detection problem where, for each group of 5 grayscale 32x32 images, 4 share a hidden attribute and 1 is an outlier. We placed 3rd place out of 105 teams!'
# date:
# venue: 
#slidesurl: 
paperurl: "/files/comp551_3.pdf"
#bibtexurl: 
#citation:
---

We address a novel outlier detection problem where, for each group of 5 grayscale 32x32 images, 4 share a hidden attribute and 1 is an outlier. The task is to identify the outlier’s index (5-class classification). We implement a CNN-based model with a shared encoder and MLP comparison head, enforcing a parameter limit of ≤ 25,000. Our final model achieves a public test accuracy of 80.3% with 18,373 trainable parameters. Key improvements stemmed from optimizing the number of epochs and learning rate schedule rather than increasing model size or adding complexity to the comparison head.

Our model placed *3rd place out of 105 teams* with an accuracy of 74.4 percent! (see [kaggle](https://www.kaggle.com/competitions/mcgill-comp551-winter2026-a3/leaderboard))

[View Paper](/files/comp551_3.pdf) |
[Download Code](/files/comp551_3_code.ipynb)

![Model Architecture](/images/comp551a3diagram.jpg)