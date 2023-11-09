## How to Read

```
import numpy as np
path_to_data = "YOUR_PATH_HERE"
date = 2020.02.01
mu = np.loadtxt('{}\{}\mu'.format(path_to_data, date))
Q = np.loadtxt('{}\{}\Q'.format(path_to_data, date))
```
