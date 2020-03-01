---
layout: post
published: true
title: My first dabble
subtitle: is ml glorified stats?
date: '2018-06-21'
image: /img/figure_6.jpg
gh-repo: ShahzaibP
gh-badge:
  - follow
comments: true
---
Hello again!

As the title suggests, this is a breif rant just about that claim.

My first dabble in machine learning was just me playing with a little data back in freshman year. Useable data, rather cleaning data so that it is useable, is a far more difficult job than what one might anticipate. As was my case, but I quickly realized that there is immense amounts of already clean data up for grabs. As for my first dabble, I started by grabbing yearlong stock price history for Berkshire Hathaway - A and got to work. Had to fix the dates, but still. Used Support Vector Machine and Linear Regression through scikit-learn and was able to generate a very close estimate of what the prices might look like in the near future. Historical prices do not affect much of the stock market which is moreso influenced by factors like unexpected news, weather, time of the year, current state of social issues and many other factors that affect the market in general. Nonetheless, it is still a viable source to predict a shortrun outcome, after all we are also working with linear regression.

And this is where my stance comes in. Walking through this project, I did realize that statistics is whats on play here but the way the models are engineered it is a little more than "just stats". To acheive an outcome that gives us certainity we need to familiarize ourselves with the concepts of linear algebra, calculus, analysis and needless to say, robust programming.

As for this particular case, a way better way to predict would be to use Stochastic processes. Markov Chains would be a better way to compute such data to generate promising outcomes, and I can't wait to dive deep into the coursework the following semester.

Find my work [here](https://github.com/ShahzaibP/stock-predictor-w-svm).
