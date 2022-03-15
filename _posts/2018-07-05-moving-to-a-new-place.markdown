---
layout: post
title:  Presidential Tweet Analysis
date:   2021-11-23 00:00:35 +0300
image:  05.jpg
tags:   Natural Language Processing
---

The goal here was to understand triggers and sentiments that riles the audience up and connects them to a said content. The following behind a tweet posted has its own custom triggers. The idea behind this project is to understand over time, what kind of  key words used by one of the US presidents impacted the number of retweets he received on his Tweets. 

Source Data - 
https://www.thetrumparchive.com/

Libraries Used - 
- tidyverse
- tidytext
- tokenizers
- stringr
- glmnet

Models Used - 
Sparse Regression Model using glmnet package alongside Cross-Validation to select the sparsity parameter lambda

Min Lambda Noted - 218.8954

Results - 
1. #fnn has the highest positive coefficient noted that impacts retweets
2. Some other key terms noted here are photographs, quarantine, nuclear in the top 20 coefficients that positively impact retweets

| Code is available to be viewed on Github on request |
