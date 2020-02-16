---
title: NLP Next Word Prediction
author: ~
date: '2020-02-16'
slug: nlp-next-word-prediction
categories: [NLP, Apps]
tags: [NLP, tidytext, Apps]
lastmod: '2020-02-16T20:24:09Z'
layout: post
type: post
highlight: no
image: "/img/NLP.png"
---

**NLP Predict the next word.**

As the final part of the Coursera R Programming Course I had to build an App that would predict the next word as a user started to type in words so that after min. 3 words the next word is predicted. Similar to the function of some smartphones.

The app can be found here:
https://nicey80.shinyapps.io/NLP_App_v2/

{{<figure src="/img/NLP.png">}}


## The App

The App was created primarily using the tidytext package to ingest the corpus data (tweets, blogs and news articles) and create the relevant ngram models and then using dplyr & data.table to process the search based on the most likely outcome from the gram models.

Full Code is available here:
https://github.com/Nicey80/NLP_CAP/blob/master/app.R

### Useful Resources

When building the app I found Julia Silge & David Robinson's excellent book on tidytext and excellent resource to be able to refer to to work through examples etc. The book can be found here for reference:
https://www.tidytextmining.com/

