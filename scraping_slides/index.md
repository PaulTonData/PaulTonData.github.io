---
title       : Exploratory NLP and Veggieboards.com
subtitle    : 
author      : Paul Ton
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- .class #id 

## Introduction
  
<img src='./assets/img/veggieboards.jpg'/>
* units of analysis
  - users
  - threads
  - posts 
  
<img src='./assets/img/forums.jpg'/>

---  

## Scraping
* research  
<img src='./assets/img/alexa.jpg'/>  
* plan
  - two pass strategy
  - proxy rotation
  - MongoDB storage
  - ethical considerations

---  

## Dataset

* summary
  - 447,876 posts
  - 21,910 threads
  - 14,612 users  
  
<img src='./assets/img/threads_per_user.png' height='360' width='480'/>
<img src='./assets/img/posts_per_thread.png' height='360' width='480'/>


---  

## Dataset

* post  
<img src='./assets/img/post.jpg' />  

---

## Dataset

* cleaned  
<img src='./assets/img/clean_text.jpg' />  

---
  
## Natural Language Processing

### workflow
  1. text normalisation
    - cleaning, tokenization, stemming / lemmatization
  2. phrase modeling
  3. dictionary creation
  4. Latent Dirichlet Allocation

---  

## Natural Language Processing  

* processed  
  
<img src='./assets/img/processed.jpg' />

* LDA
https://paultondata.github.io/vis/LDAthreads.html  
https://paultondata.github.io/vis/LDAusers.html

---

## Discussion / Future Work

 * authorship attribution
  - user meta-data  
 * troll detection  
 * deceptive opinion spam

---

## References

* Veggieboards:  
http://www.veggieboards.com
* Alexa page for Veggieboards:  
https://www.alexa.com/siteinfo/veggieboards.com
* Analyzing Internet Forums:  
http://psycnet.apa.org/record/2012-24262-002
* Modern NLP in Python:  
https://www.youtube.com/watch?v=6zm9NC9uRkk
https://github.com/skipgram/modern-nlp-in-python/tree/master/executable
* Improving LDA Topic Models:  
https://dl.acm.org/citation.cfm?id=2484166
* Authorship Attribution with LDA:  
http://aclweb.org/anthology/W11-0321
* Zipf's law:  
https://simple.wikipedia.org/wiki/Zipf%27s_law
