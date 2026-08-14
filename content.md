NumPy contains functions which applies the sine, cosine and tangent functions elementwise to arrays:

```py-cell
import numpy as np

a = np.array([0, np.pi/2, np.pi])

print(np.sin(a))
print(np.cos(a))
print(np.tan(a))
```

These functions interpret the input as radians.