---
title: "Machine Learning Project: Perceptron"
date: 2018-01-28
tags: [machine learning, data science, neural network]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Machine Learning, Perceptron, Data Science"
mathjax: "true"
---

First I would like to say, welcome to the inaugural post in my Exploratory Data Analysis section.

Typically, EDA is your first venture into a dataset. While you may know general information about the subject matter or have preconceived notions of the features and records, EDA provides us with the chance to discover the intricacies of our data. It also provides us with an understanding on how the values inhabit the data set.
(Quote: How do you find a needle in a haystack? You bring a magnet. EDA is said magnet)
While a lot of data science savants know techniques used in EDA, when most of us (myself included) actually get our hands on a new dataset the most obvious question is “How and where do I start with EDA?” 
This is a valid question because EDA doesn’t have a true procedural form. While you might get used to performing the same type of analysis, the nature of EDA involves discovering the unknown or proving that a known is known. I’ve found that the best way to conduct EDA is by:
1.	Asking a series of questions about my data.
2.	Use EDA techniques to answer my questions.
3.	Digest those answers (Think about what I've found and what it means).
4.	Use those answers to ask new questions or reutilize the older questions.


I don't know about you, but I love games. Games tend to bring the best and the worse out of everyone. Honestly, playing a game like Monopoly or Settlers of Catan with a group of people and still remaining friends afterwards is like the litmus test of everlasting camaraderie.
I like games so much, I started to develop one myself. Elaborating on the game isn't the real focus of this post but it helps with the question generation of EDA. The game is a super hero vs. super villain card game. Players will get to develop their character further and then play objective based matches. This happens 3 times and depending on the objective described one team (heroes or villains) is declared the winner. 
I completed a prototype of the game but I was still wondering I could gather insight  to intelligently mold the prototype into an official game. Then it clicked "*I could use data science to help me in my endeavors*"
### Materials and Methods
This is where you can find the [dataset]( https://www.kaggle.com/gabrio/board-games-dataset).
It looks like the person who gather this data had the same idea I had only on a much **broader** scope.
Here are a few of the packages I used.
```r
library(tidyverse)
library(corrplot)
library(stringr)
```