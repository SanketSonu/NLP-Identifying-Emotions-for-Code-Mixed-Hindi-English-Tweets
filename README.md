There is no publicly good quality data and pre-trained models for Code Mixed Hindi–English data, also it is expensive to collect, pre-process and run various machine and deep learning models. How efficiently can machine and deep learning models predict emotions from Code Mixed Hindi–English tweets? -> This is my MSc. Data Analytics - Thesis

Steps:

Extracted bilingual Code Mixed Hindi-English tweets using Twitter's official API 'Tweepy'.
Performed data cleaning by removing all those tweets which are less than 2-3 words and tweets that are completely in English or Hindi script. Cleaned noises such as links, RT, @, emojis, flags, etc. Converted many words in which had the same meaning but users used different spellings, such as 'hum', which means 'we' in English can be written as 'humm', 'hm, 'humm', etc. Most of those words are changed into a single word using Python's 'Regular Expression - re library'.
Manually annotated dataset into 7 emotions classes: Happy, Sad, Angry, Fear, Disgust, Surprise, or No emotions.
Performed pre-processing by removing punctuations, stopwords, numbers, converting all texts into lower case. This is using 1036 Hindi--English stopwords from Source--> https://github.com/TrigonaMinima/HinglishNLP/blob/master/data/assets/stop_hinglish
Extracted features using Vectorizers and Word Embeddings.
Implemented supervised machine learning models: SVM, Multinomial Naive Bayes, Logistic Regression, and Random Forest.
Implemented supervised deep learning models: CNN and LSTM.
Evaluated Results.
I Will be uploading the project Report in 'Feb - 2022' because right now I have submitted the paper and if I upload it here, there may be a chance of 'Plagiarism'.
Note: I'm uploading only Tweet's ID as a dataset because of Twitter Policy, which says I can't share data publically. I will discuss with my supervisor and will check if I can share the exact dataset publically or not.

Thanks :)
