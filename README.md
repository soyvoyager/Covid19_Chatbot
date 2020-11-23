# Covid19_Chatbot
This is basic implementation of Chatbot using python and NLTK strategies. Basically I am using word tokenization method to extract answers close to the keywords used in questions by user. 
# Outline
* [Idea of project](#Idea)
* [Information accessed](#Information accessed)
* [Pre-requisites](#pre-requisites)
* [How to run](#how-to-run)


## Idea
The idea of this project was not to create some SOTA chatbot with exceptional cognitive skills but just to utilise and test my Python skills.This is an easy implementation of Chatbot system with excellence of NLTK. As I am in starting phase of exploring NLP so am keeping things simple.

## Information accessed
The chatbot is trained on corona virus information by wikipedia. you can check out this article here:**[Corona information source(covid.txt)](https://en.wikipedia.org/wiki/Coronavirus_disease_2019)**


## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```

## How to run
* Colab Notebook [https://colab.research.google.com/drive/12qKtKB5NsNsFKcR8FydaPF24lK6X3k7X#scrollTo=9I6yxmW5H0Jd)


```
Covid_Chatbot.ipynb
