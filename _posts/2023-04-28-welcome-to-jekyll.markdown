---
layout: post
title:  "ML Interview Question Bank"
date:   2023-04-28 21:14:52 -0500
categories: jekyll update
---

Having recently spent a good portion of my time interviewing with companies for ML roles, I realised that I couldn't find a comprehensive list of topics or questions to go through before any ML interview. [Rohan](https://rohankumar.github.io/) and I compiled this list of questions and references as we interviewed with numerous companies for the second half of last year. 

### Questions:

#### General:

1. What is bias-variance tradeoff? Which models exbhibit low variance?
2. How can we avoid underfitting and overfitting?
3. How do you deal with imbalanced data? 
4. What is the difference between L1 and L2 regularisation? Why does L1 drive weights to zero?
5. Why do we use batchnorm?
6. What is the difference between SGD and GD? 
7. Compare Momentum, RMSProp, Adagrad and Adam.
8. How do you decide between standardization and normalization?
9. What is the reparameterization trick?
10. What is Xavier init and why do we use it?
11. When no. of features is greater than number of  examples, why do we not have a unique solution to minimize the residual sum of squares?
12. What is inductive bias?
13. How can we reduce the dimensionality of a large dataset? (PCA)
14. Express the bias variance decomposition as MSE loss. 
15. What is the effect of batch size on training?


#### Models:
1. What are the drawbacks of K-means algorithm?
2. How can you choose the optimal k for K-means?
3. In KNN, if k=1, does it have high variance or bias?
4. Compare bagging and boosting methods.
5. What is weakly supervised learning?
6. What are the basic assumptions to be made for linear regression?
7. Why would we not pass ordinal values to a model for categories?
8. What is the Kernel trick for SVMs?
9. How do you do dropout in RNNs? How does it work during test time? 
10. What are the assumptions we make for Naive Bayes algorithm?
11. What is the difference between Naive Bayes and Logistic Regression?
12. In linear regression, why do we use sum of squares?
13. What is the gradient boosting algorithm? Difference between Gradient boosted Decision Trees and Random Forests?
14. What is the difference between SVMs and Logistic Regression? Write down the loss functions.
15. What is the difference between Collaborative and content based filtering?


#### Evaluation
1. What is Type I and Type II error?
2. What is precision, recall, F1 and ROC curve?
3. How do you do k-fold validation for time series data?
4. How do we evaluate multi-label classification problems?
 

### Useful References:
<ol>
<li> Chip Huyen's <a href= "https://huyenchip.com/ml-interviews-book/">book</a> on ML interviews gives a comprehensive overview of the interview process. </li>

<li> Patrick Halina has a really good <a href="http://patrickhalina.com/posts/ml-systems-design-interview-guide/#ml-systems-questions">Systems Design guide</a>. I have used this as a reference for every System Design interview I have ever done. </li>

<li> CS 229 <a href="https://stanford.edu/~shervine/teaching/cs-229/"> Cheatsheets </a> are useful for a quick revision of concepts. </li>

<li> If you are interviewing for NLP roles, I would recommend reading the <a href="https://arxiv.org/abs/1810.04805">BERT paper </a> and <a href="https://arxiv.org/abs/1706.03762"> Transformer paper </a>before the interview. </li>






<!-- Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->
