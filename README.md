## Simulation of customer movement in a supermarket with pygame and Markov chains
- Used __data of customer movement__ in a supermarket ('timestamp', 'customer_no', 'location') to derive a __transition matrix__, with probabilities for customers moving from one location to another (i.e. dairy, spices, fruit, drinks)
- Project had __strong OOP focus__, e.g., defined __customer and supermarket classes__ to conduct a (first) __"Markov Chain Monte Carlo"__-simulation (MCMC)
- Leveraged __pygame to visualize MCMC__ (inspired by this [great tutorial](https://www.youtube.com/watch?v=JtiK0DOeI4A&t=1512s)) - for this, further detailed the customer and supermarket classes (using class inheritance) and __added spot and grid classes to control visual elements in pygame__

<img src="https://github.com/piwi3/supermarket_simulation/blob/main/code/pygame_supermarket_simulation.gif" width="450"><br/>
_Figure 1: A few seconds of the built supermarket simulation/visualization in pygame_
