---
layout:     post   				   
title:      Sentiment Analysis Note 1
subtitle:   
date:       2018-10-07
author:     James Cao
header-img: img/post-bg-2015.jpg 	
catalog: true 					
tags:								
    - Sentiment Analysis
---

## Sentiment Analysis Terminologies
> N-gram model:
An n-gram model is a contiguous sequence of n items from a given of text/sentence.


Examle: We are given a sentence 'I love you'.
1. 1-gram/unigram model: [('I'),('love'),('you')]
2. 2-gram/bigram model: [('I','love'),('love','you')]
3. 3-gram/trigram model: [('I','love','you')]

> Prior polarity scoring:
With the resource of Dictionary and WordNet, each word will be assigned a pleasantness score ranged from 1 (Negative) to 3(Postive).

Note: not every score can be found.

> POS of Words:
It is simply tag attached to single word.

Example:
1. The word<strong>big</strong> will be tagged as JJ (adjective).
2. The word<strong>door</strong> will be tagged as NN (noun).

Note:
You are free to invent your own tags, as long as they are used consistently.
