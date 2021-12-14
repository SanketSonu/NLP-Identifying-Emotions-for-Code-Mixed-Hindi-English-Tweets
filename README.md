# NLP-Identifying-Emotions-for-Code-Mixed-Hindi-English-Tweets
There  is  no  publicly  good  quality  data  and  pre-trained  models  for  Code  Mixed  Hindi–English data, also it is expensive to collect, pre-process and run various machine and deep learning models.  How efficiently can machine and deep learning models predict emotions from Code Mixed Hindi–English tweets? -> This is my MSc. Data Analytics - Thesis 

Steps:
1. Extracted bilingual Code Mixed Hindi-English tweets using Twitter's official API  'Tweepy'.
2. Performed data cleaning by removing all those tweets which are less than 2-3 words and tweets which are completely in English or Hindi script. Cleaned noises such as links, RT, @, emojis, flags, etc. Converted many words in which had same meaning but users used different spellings, such as 'hum', which means 'we' in english can be written as 'humm', 'hm, 'humm', etc. Most of those words are changed into single word using Python's 'Regular Expression - re library'.
3. Manually annotated dataset into 7 emotions class: Happy, Sad, Angry, Fear, Disgust, Surprise, or No emotions.
4. Performed pre-processing by removing punctuations, stopwords, numbers, converting all texts into lower case. This is using 1036 Hindi--English stopwords from Source--> https://github.com/TrigonaMinima/HinglishNLP/blob/master/data/assets/stop_hinglish
5. Extracted features using Vectorizers and Word Embeddigns.
6. Implemented supervised machine learning models: SVM, Multinomial Naive Bayes, Logistic Regression, and Random Forest.
7. Implemented supervised deep learning models: CNN and LSTM.
8. Evaluated Results.
9. I Will be upload project Report in 'Feb - 2022' becuase right now I have submitted paper and if i upload here, there maybe chances of 'Palagrism'.

Note: I'm uploading only Tweet's ID as a dataset because of Twitter Policy, which says I can't share data publically. I will discuss with my supervisor and will check if i can share exact dataset publically or not.


Thanks :)
