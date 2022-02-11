<p float="left">

 <img src="https://github.com/rconfa/Histopathological-Cancer-Detection/blob/main/images/DSLogo.png" width = "500"/>
 <img src="https://github.com/rconfa/Histopathological-Cancer-Detection/blob/main/images/BicoccaLogo.png" width = "100" align="right"/>
</p>
<h2 align="center">Social Media Analytics project</h2>

# Community and sentiment analysis based on tweets
The project has set itself the goal of analyzing the thoughts and interaction of Italian users through the social posts expressed through the Twitter platform on the day of the entry into force of the new measures. In particular, we want to research the reference hubs present on the network, but also the sentiment and emotions of peoples with respect to the new limitations. 

# Motivation
One of the hottest topics in Italy in the last months of 2021 concerns the introduction of the Super Green Pass to access indoor clubs, events, gyms, etc. This security measure entered into force on 6 December 2021 and in fact no longer allows access to various services to those who have not completed the vaccination cycle.
For these reasons it was decided, for the development of the project, to analyze the impressions of the Italian Twitter community regarding the Super Green Pass,
with the aim of understanding who are the users who write and interact on the platform and if there are specific communities among the users who have commented on the introduction of this extension. We also want to analyze the **possible influencing nodes** of the network and verify the **sentiment** around them. 

# Data
The data was collected by Twitter using their API and Tweepy python package. All tweets were written on December 6th in italian languages. <br>
In data folder you can find the .csv file with all the collected tweet ([here](https://github.com/rconfa/GreenPass-Community-Sentiment-Analysis-Twitter/blob/main/Data/autore_cluster_sentiment.csv)), and you can also find two extras files that contains the sentiment extracted for each tweet ([here](https://github.com/rconfa/GreenPass-Community-Sentiment-Analysis-Twitter/blob/main/Data/text_sentiment.csv)) and the aggregated sentiment per cluster ([here](https://github.com/rconfa/GreenPass-Community-Sentiment-Analysis-Twitter/blob/main/Data/autore_cluster_sentiment.csv)).

# Files
All the developed code is present in the file [Code.ipynb](https://github.com/rconfa/GreenPass-Community-Sentiment-Analysis-Twitter/blob/main/Code.ipynb).
You can also find the [<b>report</b>](https://github.com/rconfa/GreenPass-Community-Sentiment-Analysis-Twitter/blob/main/Report.pdf) and [<b>presentation</b>](https://github.com/rconfa/GreenPass-Community-Sentiment-Analysis-Twitter/blob/main/Presentation.pdf) made for the exam. Both in <i>italian language</i>.


# How to run code?
We advise you to run all the code in [Google Colaboratory](https://colab.research.google.com/) platform. All notebooks all already setted to import the necessary packages!
If you have any doubt please feel free to contact me! 

# Graph visualization
In [Pyvis_export](https://github.com/rconfa/GreenPass-Community-Sentiment-Analysis-Twitter/tree/main/Pyvis_export) folder you can find two exported interactive visualization of the network graph. You can also find a static version of the images in .jpg files if you want to see them quickly (html version is quite slow at opening).

# Results
We have found that hubs are <i>not famous people</i>, this may be an expected result due to the particular context of the no-vax discussion. In this context, the ideas and contents are more important than the celebrity of the person. <br>
Focusing on sentiment analysis we noticed that the vast majority of tweets are neutral or negative! This is a far cry from the reality where most people have been vaccinated and are not that disappointed with the new rules. 

# About us

#### Riccardo Confalonieri - Data Science Student @ University of Milano-Bicocca
  * r.confalonieri5@campus.unimib.it
  * [GitHub](https://github.com/rconfa)
  * [LinkedIn](https://www.linkedin.com/in/riccardo-confalonieri-5250b0201/)

#### Justin Armanini - Data Science Student @ University of Milano-Bicocca
  * j.armanini@campus.unimib.it
  * [GitHub](https://github.com/JArma19)

#### Chiara Cormio - Data Science Student @ University of Milano-Bicocca
  * c.cormio@campus.unimib.it
