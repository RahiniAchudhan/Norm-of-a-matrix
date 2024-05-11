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
# Register No: 212223230165
# Developed By: RAHINI.A
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/RahiniAchudhan/Norm-of-a-matrix/assets/145742838/855762c7-0e78-460f-9d7c-03117ae6658b)


### 2-Norm of a Matrix
![image](https://github.com/RahiniAchudhan/Norm-of-a-matrix/assets/145742838/b4eb8da2-2697-4c81-a6be-eef2f12aa740)

### Infinity Norm of a Matrix
![image](https://github.com/RahiniAchudhan/Norm-of-a-matrix/assets/145742838/b294788f-b319-45c7-9780-7c6acdfc2274)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
