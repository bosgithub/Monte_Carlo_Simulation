# Monte_Carlo_Simulation

#### What is Monte Carlo Simulation?

Monte carlo simulation is a method of estimating the value of an unknown quantity using the principles of *inferential statistics*

<br>

---


##### What is Inferential Statistics?

Given a population, we draw samples from this populations, the idea is the samples will exhibit the same properties as the populations from which it is drawn.

<br>
___Example___:

Say we want to find the expected age of a big class, what we would do is find the distribution of all ages in the class, multiply the age with the probability of the specific age:


<a href="https://www.codecogs.com/eqnedit.php?latex=E\left&space;[&space;A&space;\right&space;]&space;\approx&space;\sum_{a}^{}P(a)&space;*&space;a&space;=&space;20%&space;*&space;20&space;&plus;&space;50%&space;*&space;21&space;&plus;&space;30%&space;*&space;19" target="_blank"><img src="https://latex.codecogs.com/gif.latex?E\left&space;[&space;A&space;\right&space;]&space;\approx&space;\sum_{a}^{}P(a)&space;*&space;a&space;=&space;20%&space;*&space;20&space;&plus;&space;50%&space;*&space;21&space;&plus;&space;30%&space;*&space;19" title="E\left [ A \right ] \approx \sum_{a}^{}P(a) * a = 20% * 20 + 50% * 21 + 30% * 19" /></a>
<br>
What if we don't know the age distribution or probability of each specific age ahead of time? 

__Doesn't matter.__ As long as we are drawing samples __randomly__, we will get closer and closer to the expected age because samples will appear with the right frequencies.
<br>
<a href="https://www.codecogs.com/eqnedit.php?latex=E\left&space;[&space;A&space;\right&space;]&space;\approx&space;\frac{1}{N}\sum_{i}^{}a_{i}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?E\left&space;[&space;A&space;\right&space;]&space;\approx&space;\frac{1}{N}\sum_{i}^{}a_{i}" title="E\left [ A \right ] \approx \frac{1}{N}\sum_{i}^{}a_{i}" /></a>



