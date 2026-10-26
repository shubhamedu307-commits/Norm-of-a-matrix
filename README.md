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
```Python
# Register No:26013866
# Developed By:SHUBHAM KUMAR
# 1-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import  numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
norm="{:.2f}".format(norm1)
print(norm)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"


import numpy as np

InputArray=np.array(eval(input()))
twonorm=np.linalg.norm(InputArray,2)
print(f"{twonorm:.2f}")




# Infinity Norm of a Matrix

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np 
inputarray=np.array(eval(input()))
infinitynorm=np.linalg.norm(inputarray,np.inf)
print(infinitynorm)



```
## Output:
### 1-Norm of a Matrix
<br><img width="677" height="752" alt="1-Norm of a Matrix expt 7" src="https://github.com/user-attachments/assets/4753c904-1def-42ae-b127-df413fda9e84" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="605" height="801" alt="2-Norm of a Matrix expt7" src="https://github.com/user-attachments/assets/b38c55b2-4463-4bae-ad5a-3c0a4046c993" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="602" height="718" alt="Infinity Norm of a Matrix expt7" src="https://github.com/user-attachments/assets/93c4db10-3500-4411-a756-fb3cd1504cf5" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
