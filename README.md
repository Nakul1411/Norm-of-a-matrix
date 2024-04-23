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
# Register No:
# Developed By:
# 1-Norm of a Matrix
#Program to find the one norm matrix
#Developed by : NAKUL R 
#Register number : 212223240102
 
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# 2-Norm of a Matrix

#Program to find the one norm matrix
#Developed by : NAKUL R 
#Register number : 212223240102
 
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# Infinity Norm of a Matrix

#Program to find the infinity of a matrix
#DEVELOPED BY : NAKUL R
#REGISTER NUMBER : 21222320102

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(one_matrix))



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-23 112946](https://github.com/Nakul1411/Norm-of-a-matrix/assets/138849780/2f6a6388-9c56-47e6-8f6c-602c27aa3a48)

### 2-Norm of a Matrix
![Screenshot 2024-04-23 112959](https://github.com/Nakul1411/Norm-of-a-matrix/assets/138849780/dd253bec-d2db-453e-baee-dd81b9016708)

### Infinity Norm of a Matrix
![Screenshot 2024-04-23 113009](https://github.com/Nakul1411/Norm-of-a-matrix/assets/138849780/7aa8874c-3ded-4766-9aaf-f577b887937e)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
