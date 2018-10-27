### Legend and a grid

In addition to the title, and the axis labels, a grid will make your plot look much better, and if you are plotting multiple things you may want to label each one.  

Take for example if you wanted to plot `y = x` and `y = x^2`.  In this part of the course, I will show you how plot this and label each one.  As well, I will show how to add a grid to your plots!  Check out the IDE below for more information on this!
```python
# Import out libraries
import matplotlib.pyplot as plt
import numpy as np

# Create the x and y vectors
x = np.array(range(100))
y = x

# Create another vector that we can plot
y2 = x ** 2

# Make Plot #1 & add a label
plt.plot(x, y, label='plot 1 y = x')

# Make Plot #2
plt.plot(x, y2, label='plot 1 y = x**2')


# Add a title
plt.title(' Plot of y = x and y = x**2')

# Add a xlabel
plt.xlabel('x axis')

# Add a ylabel
plt.ylabel('y axis')

# Add a grid (alpha is opacity, ls is line style)
plt.grid(alpha = .4, ls = '--')

# Add a legend with the labels that we used previously
plt.legend()
```
