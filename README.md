# Intro to unsupervised learning
What is unsupervised learning?
So far, you’ve studied machine-learning algorithms for regression and classification problems. All of the algorithms that you’ve learned make use of labeled (or tagged) data, where the ground truths of the observations are given. As you already know, supervised learning is about creating algorithms that learn from labeled data. But what if you don’t have the ground truths for the observations? Are you at a dead end?

Of course not! In this lesson, you’ll dive into the challenging but exciting domain of unsupervised learning. In other words, you’ll run algorithms on unlabeled data to derive useful patterns. Unsupervised learning can be challenging, not because the algorithms are too difficult to grasp, but because the problems that unsupervised learning addresses are hard to formalize and evaluate.

The following quote highlights the current state of data science with respect to the different learning types:

“Most of human and animal learning is unsupervised learning. If intelligence was a cake, unsupervised learning would be the cake, supervised learning would be the icing on the cake, and reinforcement learning would be the cherry on the cake. We know how to make the icing and the cherry, but we don’t know how to make the cake. We need to solve the unsupervised learning problem before we can even think of getting to true AI.” —Yann LeCun, VP of Facebook and Director of AI Research

The quote above makes it clear why unsupervised learning can be exciting. It’s because most of human reasoning and learning operates in an unsupervised manner. In this lesson, you’ll step into the exciting domain of unsupervised learning by exploring two main problems that it needs to tackle:

Clustering
Dimensionality reduction
Although unsupervised learning includes other interesting topics, like anomaly detection, you’ll focus on these two subjects in this lesson.


You can use residuals from regression, classification errors, or any cost function.
## How the next iteration targets the error: 
You can weight inaccurately predicted cases high and accurately predicted cases low, you can directly model residuals, or you can model only the subset of the data that was inaccurately predicted.
Stopping rule: You can stop once you’ve run a certain number of models, or once the amount of variance explained by the most recent iteration of the model is lower than some threshold. Or you can stop once the change in weights between the two most recent model iterations is lower than some threshold.
