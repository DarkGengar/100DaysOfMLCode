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

**Thoghts:** Chapter 5 of the course Move 37 seems to be very interesting.  
