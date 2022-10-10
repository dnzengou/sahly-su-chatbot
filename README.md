# Building a Simple Chatbot from Scratch in Python (using NLTK)

![Sahly demo](https://github.com/dnzengou/sahly-su-chatbot/blob/main/img/sahly-demo.png?raw=true)

Historien om chatbots går tillbaka till 1966 när ett datorprogram som heter ELIZA uppfanns av Weizenbaum. Den imiterade språket hos en psykoterapeut från endast 200 rader kod. Du kan fortfarande prata med det här: [Eliza](http://psych.fullerton.edu/mbirnbaum/psych101/Eliza.htm?utm_source=ubisend.com&utm_medium=blog-link&utm_campaign=ubisend). 

På liknande linjer, låt oss skapa denna mycket grundläggande chatbot för SU som heter Sahly genom att använda Pythons NLTK-bibliotek. Det är en mycket enkel bot med knappt några kognitiva färdigheter, men ändå ett bra sätt att komma in i NLP och lära känna chatbots.

För detaljerad analys, se referensbloggen som inspirerade detta projekt:<br>
[Building a Simple Chatbot in Python (using NLTK](https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e)

***

<!--

# Outline
* [Motivation](#motivation)
* [Blogpost](#blogpost)
* [Pre-requisites](#pre-requisites)
* [How to run](#how-to-run)


## Motivation
The idea of this project was not to create some SOTA chatbot with exceptional cognitive skills but just to utilise and test my Python skills.This was one of my very first projects, created  when I just stepped into the world of NLP and I thought of creating a simple chatbot just to make use of my newly acquired knowledge.

## BlogPost
For detailed overview, here is the accompanying blog titled:**[Building a Simple Chatbot in Python (using NLTK)](https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e)**


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
-->

## Hur man startar
<!-- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dnzengou/sahly-su-chatbot/)-->

* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dnzengou/sahly-su-chatbot/929af9ab96898236db7be4730940216e82e3533f?urlpath=lab%2Ftree%2FSahly.ipynb)

* [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xT_yb5oK6l8sp8ZBIAo4W28zQnzd0AXX)

Du kan starta [sahly.ipynb](https://github.com/dnzengou/sahly-su-chatbot/blob/master/sahly.ipynb) som även innehåller steg för steg instruktioner.
* Genom terminal
```
python sahly.py
```
