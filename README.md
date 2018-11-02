# CMPE 251 : Data Science and Social Media Analysis



## Topics Covered So Far

1. Compare Basic Machine Learning Algorithms
 - LinearRegression
 - LogisticRegression
 - Decision Tree
 - _Application_: [Introduction](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture%204/Intro%20to%20ML.ipynb) and [Test on synthethic data](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture6/Compare%20ML%20algorithms.ipynb)
 
 
2. Anomaly Detection [Kaggle Kernel](https://www.kaggle.com/pavansanagapati/anomaly-detection-credit-card-fraud-analysis)
 - [3 Sigma Rule](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture%204/9%20-%20Simple%20Anomaly%20Detector%20in%20Real%20Time.ipynb) and [link](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture%204/Normal%20Distribution%20and%203%20Sigma%20Rule.ipynb)
 - [Isolation Forest](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture6/Isolation%20Forest.ipynb)
 - _Application_ : [Google Trend Data](https://trends.google.com.tr/trends/explore?date=today%205-y&geo=TR&q=darbe)

3. Intro 2 Text Mining
 - [TF-IDF explained](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture5/TF-IDF/TF-IDF%20Explained.ipynb)
 - [Creating Text Mining Model](https://github.com/uzay00/CMPE251/blob/master/Lecture5/Intro2TextMining/1-Create%20Text%20Mining%20Model.ipynb)
 - [Test on Twitter with pre-trained model](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture5/Intro2TextMining/2-Test%20predefined%20model%20on%20a%20new%20data.ipynb)

4. Text Summarization
 - Algorithm to Extract Summary
 - _Application_ : [Summary of Wikipedia page](http://nbviewer.jupyter.org/github/uzay00/CMPE251/blob/master/Lecture7/Text%20summarization/Text%20Summarization.ipynb)
 
5. Web Scraping
 - _Application_ : ukitap
 
 
## Projects

As course advances we will add more alternative projects. You must do at least one project. You can also propose a new project. 

### 1. Sentiment Analysis On EksiSozluk

__Data Collection__
You will get data from eksisozluk with web scraper. Each student will label 500 comments on eksi. 5 label means 5 class.
 - 5 Very Positive
 - 4 Positive
 - 3 Neutral
 - 2 Negative
 - 1 Very Negative
 
 __Machine Learning__
 Use ML algorithms for Sentiment Analysis On EksiSozluk. Indicate your results.
 
 ### 2. Fake News Detection
 
__Data Collection__
You will get data from Zaytung and normal newspapers websites with web scraper. 

 - Zaytung news: 1
 - Normal newspapers: 0

 
 __Machine Learning__
 Use ML algorithms for Sentiment Analysis On EksiSozluk. Indicate your results.
 
 
 
 
 <br> <br> <br> <br> <br>
 
 ## Notes
Course web site: https://ects.bilgi.edu.tr/Course/Detail?catalog_courseId=3803945

Edx Course for Analytics in Python
- https://courses.edx.org/courses/course-v1:ColumbiaX+BAMM.101x+2T2017/course/

__Algorithm vs Machine Learning__
> We have in mind some desired mapping from inputs to outputs, but it's not something that's possible
for us to necessarily specify in a precise way and so we collect a training set of (X,y) examples.
The learning machine takes this training set and uses it to pick a mapping from X to Y. 



### Analyse Emotion embedded in English Words
Use NRC Lexicon: https://saifmohammad.com/WebPages/nrc-vad.html

### 1st Project: Create a New Elvis Presley Song Lyric
Use __textrank algorithm__ to create a new song lyric from a popular singer. 
Then use it to create a combined lyric of various singers.

> we are defining a different relation, which determines a connection between two sentences if there is a “similarity” relation between them, where “similarity” is measured as a function of their content overlap.

<p align="center">
  <img src="similairty.png" width="350"/>
</p>
