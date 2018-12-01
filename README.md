# 100DaysOfMLCode
Repository of the AI journey 100 Days of ML Code

# 100 Days Of ML Code - Log

## Day 1 : September 23, 2018

**Today's Progress:**: Begin with the journey and watch lecture 1 Introduction to 
RL of David Silver's RL course

**Thoughts:** I am very excited.

**Links:**

lecture 1 of David Silvers [RL Course](https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-)

## Day 2: September 24, 2018

**Today's Progress:**: Start with chapter 3 Monte Carlo Methods of the course Move 37,
finished lecture 3.1 and 3.2 of the course and start with lecture 4 Model-Free Prediction 
of David Silver's RL course.

**Thoughts:** I learned methods to work with unknown MDPs.

**Links:**

[Lecture 3.1 of Move 37](https://www.youtube.com/watch?v=kYWw6GBRjVk)
[Lecture 4 of David Silver's RL course](https://www.youtube.com/watch?v=PnHCvfgC_ZA&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-&index=4)

## Day 3: September 25, 2018

**Today's Progress:** I have finished lecture 3.5 of the course Move 37 and continue watching
lecture 4 of David Silver's RL course.

**Thoughts:** I have understand the concepts of first-visit MC policy evaluation and
every-visit MC policy evaluation however I am a bit confused where the function
gets the reward values for the mean return when the reward and transition 
function is unknown.

## Day 4: September 26, 2018

**Today's Progress:** I have started lecture 3.3 of the course Move 37 and read
chapter 5 Monte Carlo Methods of Sutton's RL book.

**Thoughts:** I have a lot of questions I want to answer
during this week and I hope I can find the answers.

**Links:**
[Sutton's RL book](http://incompleteideas.net/book/bookdraft2018jan1.pdf)

## Day 5: September 27, 2018

**Today's Progress**: Continue reading lecture 3.3 of the course Move 37.

**Thoughts**: The Multi Armed Bandits methods seems to be useful for RL and I am
interested to see how well it works for RL.

## Day 6: September 28, 2018

**Today's Progress:** I have watched the livestream TPU Machine Learning by Siraj Raval
and read more about Exploration and Exploitation methods.

**Thoughts:** The topic about TPUs is very interesting and I will give it a try
when I start with Deep Learning.

**Links:**
[TPU Machine Learning LIVE](https://www.youtube.com/watch?v=jgNwywYcH4w)
[Multi Armed Bandits Methods](https://www.searchenginepeople.com/blog/16072-multi-armed-bandits-ab-testing-makes-money.html)

## Day 7: September 29, 2018

**Today's Progress:** I have watched lecture 3.4 Monte Carlo Coding 
Tutorial and complete lecture 3.3 Exploration vs. Exploitation and Multi-Armed Bandits 
of the course Move 37.

**Thoughts:** I have learned how a model free algorithm estimates the
value function. As I have understood it the algorithm needs the reward of
the terminate state to estimate the value function.

**Links:**
[MC Coding Tutorial](https://www.youtube.com/watch?v=mMEFFN1H5Cg)

## Day 8: September 30, 2018

**Today's Progress:** I have finished lecture 3.4, 3.5, 3.6 and 3.7 of the course Move 37
and I start coding the MC methods I have learned in chpater 3 Monte Carlo Methods.

**Thoughts:** I have some trouble to implement mathmatical equations into code
but I hope I can handle this during the next weeks.

**Links:**
[MC Coding Tutorial](https://www.youtube.com/watch?v=mMEFFN1H5Cg)
[MC Simulation](https://www.vertex42.com/ExcelArticles/mc/MonteCarloSimulation.html)
[MC Methods](https://www.kth.se/social/files/58b941d5f276542843812288/RL04-Monte-Carlo.pdf)
[Q learning for Trading](https://www.youtube.com/watch?v=rRssY6FrTvU)

## Day 9: October 1, 2018

**Today's Progress:** I have continue coding the Monte Carlo Methods and start Chapter 4 Model Free Learning
of the course Move 37.

**Thoughts:** I have learned the concept of TD learning. It seems to be a good technique
for real world probelms because of the step-by-step update function.

**Links:**
[Mathematics of Dopamine](https://www.youtube.com/watch?v=-vhYoS3751g)
[TD Learning](https://www.youtube.com/watch?v=f4zTDRavVq0)
[Chapter 6 of Sutton's book](http://incompleteideas.net/book/bookdraft2018jan1.pdf)

## Day 10: October 2, 2018

**Today's Progress:** I have started coding the TD(0) learning algorithm continue coding MC methods.

**Thoughts:** It is very difficult to code the algorithms but I will never give up

## Day 11: October 3, 2018

**Today's Progress:** I have read chapter 6 Temporal-Difference Learning of Sutton's RL
book and finished my first implementation of the TD(0) prediction algorithm.

**Thoughts:** I understand the topic better and better and make my first
success. The agent won 1,200 of 10,000 games.

**Link:**
[Chapter 6 of Sutton's book](http://incompleteideas.net/book/bookdraft2018jan1.pdf)

## Day 12: October 4, 2018

**Today's Progress:** Today I have implemented the SARSA algorithm, finished reading chapter 6 
Temporal-Difference Learning of Sutton's RL book and read the reading assignments of 
lecture 4.2 of the course Move 37.

**Thoughts:** It makes me happy to see the success of my efforts I did so far.
The SARSA agent won 1,775 of 10,000 games on average and the best result
the agent did so far is 3032 wins.

**Links:**
[Chaapter 6 of Sutton's RL book](http://incompleteideas.net/book/bookdraft2018jan1.pdf)
[Reward-Based Learning, Model-Based and Model-Free](https://www.quentinhuys.com/pub/HuysEa14-ModelBasedModelFree.pdf)
[Model-Free Deep RL](https://bair.berkeley.edu/blog/2018/04/26/tdm/)

## Day 13: October 5, 2018

**Today's Progress:** I have implemented the Q-Learning algorithm, compare it with the SARSA algorithm
and read one paper of the reading assignment.

**Thoughts:** For the environment "Frozen Lake" the result of the algorithms seems to be quite similiar.
The paper about Temporal-Difference Models looks very interesting but also quite difficult.

**Links:**
[Paper Temporal Difference Models](https://arxiv.org/abs/1802.09081)

## Day 14: October 6, 2018

**Today's Progress:** I have extend the SARSA and Q-Learning algorithm with a variable learning and
exploration rate, finished lecture 4.5 Q-Learning Tutorial for Ride Sharing of the course Move 37
and completed the quiz of  chapter 4 of this course. The agent is now a lot better 
and won 70% of 50000 episodes.

**Thoughts:** This week I get a good understanding of TD Learning.
Tomorrow I will try to compare the MC methods with the TD Learning methods.

**Links:**
[Lecture 4.5 Q-Learning Tutorial of Move 37](https://www.youtube.com/watch?v=tU6_Fc6bKyQ)

## Day 15: October 7, 2018

**Today's Progress:** I have finished dhapter 4 of the course Move 37 and
started to implement the Monte Carlo method.

**Thoughts:** I hope I can implement the Monte Carlo method in the next few days.
to compare it with the TD Learning methods. I am excited to see the
next chapter of the course Move 37.

## Day 16: October 8, 2018

**Today's Progress:** I have some trouble with my implementation of the Monte Carlo mehtod and
I hope I can fix the problem in the next few days. Start chapter 5 RL in Continuous Spaces of the
course Move 37.

**Thoughts:** Chapter 5 of the course Move 37 seems to be very interesting.  

## Day 17: October 9, 2018

**Today's Progress:** I watched lecture 5.2 Augmented Random Search Tutorial of the course Move 37.

**Thoughts:** The ARS algorithm is interesting but I have trouble to implement it.

**Links:**
[ARS algorithm](https://www.youtube.com/watch?v=2P2Dj5PX5cg&t=226s)

## Day 18: October 10, 2018

**Today's Progress:** I have read a paper about ARS and watch lecture 5.1 Inverse
and Forward Kinematics.

**Thoughts:** Robotics is a very fascinating topic and I want to go deeper into
this field.

**Links:**
[Robotic Manipulation Explained](https://www.youtube.com/watch?v=mCI-f71MAvY)
[ARS Paper](https://arxiv.org/abs/1803.07055)

## Day 19: October 11, 2018

**Today's Progress:** I watched the video 'How to Get an AI Internship' by Siraj Raval and
continued reading yesterday's paper.

**Thoghts:** The video was very inspiring and I will try to follow some of the
tipps in the future when I am ready to start searching for an internship.

**Links:**
[ARS Paper](https://arxiv.org/abs/1803.07055)
[How to Get an AI Internship](https://www.youtube.com/watch?v=CGTn0ceOaOM)

## Day 20: October 12, 2018

**Today's Progress:** I watched the livestream Quantum Machine Learning by Siraj Raval.

**Thoughts:** I am very interested in Quantum Programming and excited to see
more about this topic in the future.

**Links:**
[Quantum Machine Learning LIVE](https://www.youtube.com/watch?v=AAO4oq2M_48)

## Day 21: October 13, 2018

**Today's Progress:** I read the lecture 5.4 Inverse Kinematics of the course Move 37
and tried to implement the ARS algorithm but the gym environment 'BipedalWalker-v2'
did not work because of dependency problems with Box2D.

 **Thoughts:** Currently it is very difficult and I have technical and understanding problems
 but I try to continue my journey.
 
 ## Day 22: October 14, 2018
 
 **Today's Progress:** I have continued read the lecture 5.4 Inverse Kinematics of the course Move 37
 watched the video 'Coding Challenge #64.1: Forward Kinematics' by The Coding Train and
 fixed the dependency issues of Box2D.
 
 **Thoughts:** I am glad that the issues are fixed and I can continue the course Move 37.
 
 **Links:**
 [Forward Kinematics](https://www.youtube.com/watch?v=xXjRlEr7AGk)
 
 ## Day 23: October 15, 2018
 
 **Today's Progress:** I watched the video 'SQL Database Optimization' by Siraj Raval and
 watched the first 5 videos of Python 3 Pygame tutorial series by Sentdex.
 
 **Thoughts:** I have a lot of work to do in the course Move 37 and I hope I can catch up
 the missing lectures of the last week.
 
 **Links:**
 [SQL Database Optimization](https://www.youtube.com/watch?v=Rw3ewEXOKC8) \
 [Pygame Tutorial Series](https://www.youtube.com/watch?v=ujOTNg17LjI&list=PLQVvvaa0QuDdLkP8MrOXLe_rKuf6r80KO)
 
 ## Day 24: October 16, 2018
 
 **Today's Progress:** I began with chapter 6 'Deep Reinforcement Learning' of the course Move 37
 and watched lecture 6.2 'Deep Q-Learning Pong Tutorial'.
 
 **Thoughts:** I want to see how much better the Deep Q-Learning algorithmn is compared to the 
 normal Q-Learning algorithm.
 
 **Links:**
 [Deep Q-Learning Pong Tutorial](https://www.youtube.com/watch?v=pST6caY3mu8)


## Day 25: October 17, 2018

**Today's Progress:** I have read several articles about Deep Q-Learning for a
better understanding of the magic behind the scenes.

**Thoughts:** Deep Q-Learning is quite interesting and I will implement
the algorithm during this week.

**Links:** \
[Deep Q-Learning with Keras and Gym](https://keon.io/deep-q-learning/) \
[A Beginner's Guide to Deep Reinforcement Learning](https://skymind.ai/wiki/deep-reinforcement-learning) \
[An Introduction to Deep Q-Learning: let's play Doom](https://medium.freecodecamp.org/an-introduction-to-deep-q-learning-lets-play-doom-54d02d8017d8)

## Day 26: October 18, 2018

**Today's Progress:** I continued reading the article 'Deep Q-Learning with Keras and Gym' and
watch the video 'The Anti Facebook' by Siraj Raval.

**Links:** \
[The Anti Facebook](https://www.youtube.com/watch?v=T5zIlWSMlU8&t=502s) \
[Deep Q-Learning with Keras and Gym](https://keon.io/deep-q-learning/)


## Day 27: October 19, 2018

**Today's Progress:** I have started with PyTorch and read the 'Getting Started Series' on the PyTorch site.

**Thoughts:** PyTorch is a powerful library and I will create some projects with the library.

**Links:** \
[Deep Learning with PyTorch: A 60 Minute Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)

## Day 28: October 20, 2018

**Today's Progress:** I have finished the tutorial 'Deep Learning with PyTorch: A 60 Minute Blitz'.

**Links:** \
[Deep Learning with PyTorch: A 60 Minute Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)

## Day 29: October 21, 2018

**Today's Progress:** I have worked a lot with the PyTorch library and tried to implement a dataset class.

**Thoughts:** I am very excited about PyTorch and how many tools they provide for the development of
neural networks (computations, dataset class, dataloader).

**Links:** \
[Data Loading and Processing Tutorial](https://pytorch.org/tutorials/beginner/data_loading_tutorial.html#sphx-glr-download-beginner-data-loading-tutorial-py) \
[Dataset examples](https://github.com/pytorch/vision/tree/master/torchvision/datasets)


## Day 30: October 22, 2018

**Today's Progress:** I have continued working on the dataset class, read a deep learning book
and watched the video 'Meta Learning' by Siraj Raval.

**Thoughts:** Data preprocessing is very time consuming.

**Links:** \
[Data Loading and Processing Tutorial](https://pytorch.org/tutorials/beginner/data_loading_tutorial.html#sphx-glr-download-beginner-data-loading-tutorial-py) \
[Deep Learning Book](http://www.deeplearningbook.org/contents/intro.html) \
[Meta Learning](https://www.youtube.com/watch?v=2z0ofe2lpz4)

## Day 31: October 23, 2018

**Today's Progress:** I have finished the dataset class for my image classiefier and
read in the 'Deep Learning Book' the introduction. I paused the course 'Move 37' and start
with the 6 week Deep Learning curriculum by Siraj Raval because I want to read more about Deep Learning 
before I do more RL stuff.

**Links:** \
[Curriculum Deep Learning](https://github.com/llSourcell/Learn_Deep_Learning_in_6_Weeks) \
[Intro Deep Learning Book](http://www.deeplearningbook.org/contents/intro.html)

## Day 32: October 24, 2018

**Today's Progress:** I have read the Linear Algebra part of part 1 of the Deep Learning Book and
watched the first 7 videos of the Linear Algebra series by 3Blue1Brown.

**Thoughts:** Linear Algebra is very interesting and I am excited to see it in the
Deep Learning concepts.

**Links:**\
[Linear Algebra Deep Learning Book](http://www.deeplearningbook.org/contents/linear_algebra.html) \
[Linear Algebra Series](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

## Day 33: October 25, 2018

**Today's Progress:** I have finished the Linear Algebra series by 3Blue1Brown and continued
reading the Linear Algebra part of the Deep Learning book.

**Links:**\
[Linear Algebra Deep Learning Book](http://www.deeplearningbook.org/contents/linear_algebra.html) \
[Linear Algebra Series](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

## Day 34: October 26, 2018

**Today's Progress:** I have started the probability chapter of the Deep Learning book.

**Links:**\
[Probability Deep Learning Book](http://www.deeplearningbook.org/contents/prob.html)

## Day 35: October 27, 2018

**Today's Progress:** I continued reading the probability chapter of the Deep Learning book.

**Thoughts:** It is very hard to understand all the mathematic formulas however
with good techniques such as visualization and dividing the formulas in small
pieces I got a good understanding of the formulas in this chapter.

**Links:**\
[Probability Deep Learning Book](http://www.deeplearningbook.org/contents/prob.html)

## Day 36: October 28, 2018

**Today's Progress:** I have analyzed some equations from the probability chapter of the Deep Learning book
and implement them in Python.

**Links:**\
[Probability Deep Learning Book](http://www.deeplearningbook.org/contents/prob.html)

## Day 37: October 29, 2018

**Today's Progress:** I have started with the Calculus series by 3Blue1Brown and read chapter 4 numerical
computation of the Deep Learning book.

**Links:** \
[Numerical Computation Deep Learning Book](http://www.deeplearningbook.org/contents/numerical.html)\
[Calculus Series](https://www.youtube.com/watch?v=WUvTyaaNkzM&t=0s&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=2)

## Day 38: October 30, 2018

**Today's Progess:** I have watched video 3 of the Calculus series by 3Blue1Brown.

**Links:** \
[Calculus Series](https://www.youtube.com/watch?v=WUvTyaaNkzM&t=0s&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=2)

## Day 39: October 31, 2018

**Today's Progress:** I have watched video 4 - 6 of the Calculus series by 3Blue1Brown and played around with
the ideas of the videos.

**Thoughts:** The visualizations of the mathematical problems are very helpful to understand
the ideas behind calculus.

**Links:** \
[Calculus Series](https://www.youtube.com/watch?v=WUvTyaaNkzM&t=0s&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=2)

## Day 40: November 1, 2018

**Today's Progress:** I have finished the Calculus series by 3Blue1Brown.

**Thoughts:**  I learned a lot from this series. My next steps will be to play around with the
fundamental ideas I have learned and I hope I can use them for the next stage of my journey.

**Links:** \
[Calculus Series](https://www.youtube.com/watch?v=WUvTyaaNkzM&t=0s&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr&index=2)

## Day 41: November 2, 2018

**Today's Progress:** I have did some exercises on brilliant.org and start their Artificial Neural Networks
course.

**Thoughts:** Brilliant.org is a great website to train the mathematical skills and I will do
the Artificial Neural Networks Course for the next few days to get a better intuitive understanding
of the math behind the scenes.

**Links:**
[Brilliant.org ANN course](https://brilliant.org/courses/artificial-neural-networks)

## Day 42: November 3, 2018

**Today's Progress:** I have finished chapter 1 and 2 of the course ANN on brilliant.org.

**Links:**
[Brilliant.org ANN course](https://brilliant.org/courses/artificial-neural-networks)


## Day 43: November 4, 2018

**Today's Progress:** I have finished chapter 3 of the course ANN on brilliant.org.

**Links:**
[Brilliant.org ANN course](https://brilliant.org/courses/artificial-neural-networks)

## Day 44: Novmeber 5, 2018

**Today's Progress:** I have started with chapter 4 Multilayer Perceptrons of the course ANN on brilliant.org.
I have learned about the basic structure of a single and multilayer perceptron.

**Links:**
[Brilliant.org ANN course](https://brilliant.org/courses/artificial-neural-networks)

## Day 45: November 6,2018

**Today's Progress:** I have continued with chapter 4 'Multilayer Perceptrons' of the course ANN on brilliant.org and
learned about conditional probability.

**Links:**
[Brilliant.org ANN course](https://brilliant.org/courses/artificial-neural-networks)

## Day 46: November 7, 2018

**Today's Progress:** I have learned about conditional probability and Bayes' theorem.

## Day 47: November 8, 2018

**Today's Progress:** I have continued with conditional probability.

**Links:**\
[Conditional Probability](https://brilliant.org/wiki/conditional-probability/) \
[Bayes' Theorem](https://brilliant.org/wiki/bayes-theorem/) \
[Probability And and Or](https://www.youtube.com/watch?v=psTBo1lCH1A&t=415s)

## Day 48: November 9, 2018

**Today's Progress:** I have finished chapter 4 'Multilayer Perceptrons' and 5 'Backpropagation' of the course
ANN on brilliant.org.

**Thoughts:** Now I have done the basics of Deep Learning and try to code a simple neural network
from scratch.

**Links:** \
[Brilliant.org ANN course](https://brilliant.org/courses/artificial-neural-networks)\
[Build a Neural Net in 4 Minutes](https://www.youtube.com/watch?v=h3l4qz76JhQ)

## Day 49: November 10, 2018

**Today's Progress:** I have started to implement the neural network and read the 
book 'Make Your Own Neural Network' by Tariq Rashid.

**Thoughts:** The book is a great introduction to neural networks and the math part
is very well explained.

## Day 50: November 11, 2018

**Today's Progress:** I have implemented my first Neural Network.

**Thoughts:** Now the first half of my journey is over and I am happy that I have implemented
my first Neural Network.

## Day 51: November 12, 2018

**Today's Progress:** I have worked on my Neural Network and optimize some parameters.
Furthermore I watched the video 'Move 37 Explained' by Siraj Raval.
The best result is 66.66 per cent correct answers of the MNIST Dataset so far.

**Links:**
[Move 37 Explained](https://www.youtube.com/watch?v=vI9BllT7ovg)

## Day 52: November 13, 2018

**Today's Progress:** I have started with chapter 6 'Convolutional Neural Networks' of 
the ANN course on brillian.org.

[ANN Course](https://brilliant.org/courses/artificial-neural-networks/)

## Day 53: November 14, 2018

**Today's Progress:** I have continued chapter 6 'Convolutional Neural Networks' of the
ANN course on brilliant.org.

[ANN Course](https://brilliant.org/courses/artificial-neural-networks/)

## Day 54: November 15, 2018

**Today's Progress:** I have learned about the basic concepts of Convolutional Neural Networks
and do some math exercises.

## Day 55: November 16, 2018

**Today's Progress:** I have finished chapter 6 'Convolutional Neural Networks',
watched Siraj Raval's video about CNNs and read additional resources about this
topic.

**Thoughts:** I learned a lot from the resources and I will code in the next few days
a Convolutional Neural Network from scratch with the numpy library.

**Links:** \
[The Math of Intelligence - Convolutional Neural Networks](https://www.youtube.com/watch?v=FTr3n7uBIuE&t=1782s) \
[CNNs](http://deeplearning.net/tutorial/lenet.html) \
[An Intuitive Explanation of Convolutional Neural Networks](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) \
[ANN course](https://brilliant.org/courses/artificial-neural-networks/)

## Day 56: November 17, 2018

**Today's Progress:** I have read some articles about CNNs.

**Links:** \
[An Intuitive Explanation of Convolutional Neural Networks](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) \
[CS231n Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/convolutional-networks/) \
[Understanding Convolutional Neural Networks for NLP](http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/)

## Day 57: November 18, 2018

**Today's Progress:** I have continued reading several articles about CNNs.

**Links:** \
[An Intuitive Explanation of Convolutional Neural Networks](https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/) \
[CS231n Convolutional Neural Networks for Visual Recognition](http://cs231n.github.io/convolutional-networks/) \
[A Beginner's Guide To Understanding Convolutional Neural Networks](https://adeshpande3.github.io/adeshpande3.github.io/A-Beginner%27s-Guide-To-Understanding-Convolutional-Neural-Networks/)

## Day 58: November 19, 2018

**Today's Progress:** I have learned about the Scrapy python library.

**Links:** \
[Scraoy Tutorial](https://towardsdatascience.com/using-scrapy-to-build-your-own-dataset-64ea2d7d4673)

## Day 59: November 20, 2018

**Today's Progress:** I have learned about methods to upload datasets into Google Colab.

## Day 60: November 21, 2018

**Today's Progress:** I have prepare the CIFAR-10 dataset for the neural network.

## Day 61: November 22, 2018

**Today's Progress:** I have continued preparing the CIFAR-10 dataset for the Convolutional Neural Network.

## Day 62: November 23, 2018

**Today's Progress:** I have finished the preprocessing of the CIFAR-10 dataset.

**Thoughts:** My next steps will be to code a simple Convolutional Neural Network.

## Day 63: November 24, 2018

**Today's Progress:** I have started coding the Convolutional Neural Network.

**Thoughts:** 3-D matrices can be very confusing and hard to visualize but
the best way I found is to imagine the matrix as collection of images.

## Day 64: November 25, 2018

**Today's Progress:** I have finished the forward propagation structure for the Convolutional Neural Network.

**Thoughts:** Backpropagation of a Convolutional Neural Network seems to be harder than
the Backpropagation of a Fully Connected Neural Network.

## Day 65: November 26, 2018

**Today's Progress:** I have read some articles about Backpropagation in Convolutional Layers.

**Links:** \
[Back Propagation in Convolutional Neural Networks — Intuition and Code](https://becominghuman.ai/back-propagation-in-convolutional-neural-networks-intuition-and-code-714ef1c38199) \
[Convolutional Neural Networks backpropagation: from intuition to derivation](https://grzegorzgwardys.wordpress.com/2016/04/22/8/) \
[Backpropagation In Convolutional Neural Networks](https://www.jefkine.com/general/2016/09/05/backpropagation-in-convolutional-neural-networks/) \
[Forward And Backpropagation in Convolutional Neural Network.](https://medium.com/@2017csm1006/forward-and-backpropagation-in-convolutional-neural-network-4dfa96d7b37e)

## Day 66: November 27, 2018

**Today's Progress:** I have continued reading some articles about Backpropagation in Convolutional Layer.

**Thoughts:** I have some difficulties to understand the Backpropagation method in CNN.

**Links:** \
[Derivation of Backpropagation in Convolutional Neural Network (CNN)](https://pdfs.semanticscholar.org/5d79/11c93ddcb34cac088d99bd0cae9124e5dcd1.pdf)

## Day 67: November 28, 2018

**Today's Progress:** I have read chapter 2 of the online book 'Neural Networks and Deep Learning' by Michael Nielsen.

**Links:** \
[Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/chap2.html)

## Day 68: November 29, 2018

**Today's Progress:** I have derived some functions needed for Backpropagation.

**Links:** \
[Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/chap2.html)

## Day 69: November 30, 2018

**Today's Progress:** I have worked on a Neural Network with MNIST dataset implemented in Pytorch.

## Day 70: December 1, 2018

**Today's Progress:** I have continued working on the Neural Network.
