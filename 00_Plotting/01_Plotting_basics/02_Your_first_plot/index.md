### Lets plot

Now that we have a basic grasp on vectors, we are going to put these pieces together and finally make a plot!  Here are the steps we are going to take:

1. Import the library for plotting
2. Create our vectors x and y for plotting
3. Generate the plots using matplotlib.pyplot  

Below in the IDE I implemented this for you!

**Challenge:** Rather than plotting y = x, can you plot y = x^2?

```python
# Import out libraries
import matplotlib.pyplot as plt
import numpy as np

# Create the x and y vectors
x = np.array(range(100))
y = x

# Plot!  
plt.plot(x,y)
```
