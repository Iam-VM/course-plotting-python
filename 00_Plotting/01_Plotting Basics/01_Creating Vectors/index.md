### What are we going to plot?


To begin, we need some data that we can plot.  The easiest of such is just a line where y = x.  So to begin plotting we need to create a vector for y and vector for x.  

I will do this with the following code:

```
x = list(range(100))
y = x
```

This will give me back 2 vectors. x which is `[0,1,2,3,....,98,99]` and y which is just a copy of that.  

If for example, we wanted to plot y = x^2, we would use the library numpy and just square the entire vector!

```
# Import the numpy lib
import numpy as np

# Create a vector x which is a numpy array
x = np.array(range(100))
y = x**2
```

In the next slide, we will use these new vectors to create our very first plots!!
