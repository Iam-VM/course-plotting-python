### How to label your axis

Just like adding a title to your plot is very important, axis labels to  be very useful as well.  In the matplotlib.pyplot library, it is easy to add labels to your plot and you can do this with a similar command to adding a title!

Below I added an `x` and a `y` label to our graph!
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
plt.title(' Plot of y = x')

# Add a xlabel
plt.xlabel('x axis')

# Add a ylabel
plt.ylabel('y axis')

```
