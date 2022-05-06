## Simulation of customer movement in a supermarket with pygame and Markov chains
- Used data of customer movement in a supermarket (timestamp, customer_no, lcoation) to derive a transition matrix, with probabilities for customers moving from one location to another (i.e. dairy, spices, fruit, drinks).
- Project had strong OOP focus, e.g., defined a customer class and a supermarket class to conduct a (first) "Markov Chain Monte Carlo"-simulation (MCMC)
- Leveraged pygame to visualize MCMC (inspired by this [great tutorial](https://www.youtube.com/watch?v=JtiK0DOeI4A&t=1512s)) - for this, further detailed the customer and supermarket classes (using class inheritance) and added a spot and grid class to control visual elements in pygame; simulation/visualization has been conducted with determined transition matrix and observed frequency of new customer arrivals

<img src="https://github.com/piwi3/supermarket_simulation/blob/main/code/pygame_supermarket_simulation.gif" width="450"><br/>
_Figure 1: A few seconds of the built supermarket simulation/visualization in pygame_
