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
# Register No:RITHVIK S
# Developed By :212223100045
# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot (9)](https://github.com/Rithviknathan/Norm-of-a-matrix/assets/148410509/7ed8320a-d788-4f4b-9ad8-ac996c346d51)


### 2-Norm of a Matrix
![Screenshot (10)](https://github.com/Rithviknathan/Norm-of-a-matrix/assets/148410509/e1197b07-1240-4b3f-a36d-0c8397837ae7)


### Infinity Norm of a Matrix
![Screenshot (11)](https://github.com/Rithviknathan/Norm-of-a-matrix/assets/148410509/2ac35dd6-c116-4531-bd42-0921a3985324)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
