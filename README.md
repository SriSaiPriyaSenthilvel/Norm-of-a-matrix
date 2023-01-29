# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
	
## Program:
```
Developed By: SRI SAI PRIYA.S
Register No: 22006141

1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)

Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![output](/Screenshot%20from%202023-01-29%2010-22-24.png)

### 2-Norm of a Matrix
![output](/Screenshot%20from%202023-01-29%2010-23-27.png)

### Infinity Norm of a Matrix
![output](/Screenshot%20from%202023-01-29%2010-24-26.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
