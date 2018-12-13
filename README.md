# FakeNewsIdentifier

## Sentimental Analysis on Text

## Developer

Rohit Bansal


### Hash Vectorizers and Its advantages over TF-IDF Vectorizer

Summary
Hash Vectorizer is gaining popularity as the text analysis tool. It has some distinct advantages
over TF-IDF vectorizer. In this paper Hash Vectorizer will be analyzed against traditional TF-IDF
Vectorizer. This paper will also describe some common techniques applied in real world in order
to utilize Hash Vectorizer as one of the most effective text analysis tools. The techniques
discussed will include named entity technique, combining the scores using bivariate spline etc.
Motivation
TF-IDF vectorizers is often used to create word vectors from set of documents. This vectorizer
scales the term frequency (word count) by penalizing the terms that appear widely across the
corpus. However, in such a case we require complete vocabulary in advance. In a lot of practical
cases having a prebuilt vocabulary is not possible as more and more data is being generated
every day. Further, in most scenario, data can be retained for limited period only. Since new data
is available for training while old data is getting purged, one has to recalculate all the TF-IDF
vectors based on new vocabulary. This makes TF-IDF vectors an expensive affair. In such cases,
Hash Vectorizer is very effective. This vectorizer allow the developer to do continuous training as
more and more data is available without specifying the vocabulary in advance. This feature along
with appropriate SGD parameters enables training of some foreign languages across a timeperiod
longer than retention duration of the data

### Access
the SVM classifier utility that I developed in order to analyze all these vectorizers can be found @

https://github.com/UIUC-MCSDS/CS410-Fall18-SVM-Sentiment-Analysis





