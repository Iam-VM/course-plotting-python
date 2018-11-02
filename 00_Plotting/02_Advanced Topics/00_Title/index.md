### Adding titles to your plots

We have covered the very basics of creating plots in python!  Next we will learn about some other tools that we can use to **spice** up our plots a little bit!  These methods can be used with any plot and not just the line plot that we just created.  

First up, Adding a title to your plot!  Titles are very important to help other people who are looking at your work understand your thinking process.  Because of this, we are going to add a title to our plot that says: 'plot of y = x'

Below I implemented this in the IDE!

```python
# Import out libraries
import matplotlib.pyplot as plt
import numpy as np

# Create the x and y vectors
x = np.array(range(100))
y = x

# Plot!  
plt.plot(x,y)

# Add a title
plt.title('plot of y = x')

# Show the plot
plt.show()
```
