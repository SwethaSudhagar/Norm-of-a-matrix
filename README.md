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
# Register No: 26012309
# Developed By: Swetha S
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Swetha S
RegisterNumber: 26012309 
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)







# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix
<img width="707" height="621" alt="image" src="https://github.com/user-attachments/assets/7ee9b423-6946-4dcb-9802-164eaebbcb05" />


### 2-Norm of a Matrix
<img width="640" height="656" alt="image" src="https://github.com/user-attachments/assets/708333b9-3d92-4747-9690-5798408016d1" />






### Infinity Norm of a Matrix
<img width="826" height="761" alt="image" src="https://github.com/user-attachments/assets/016ea76e-7c3a-40ea-89e1-dd537929da03" />


## Result
Thus, the python programs to find the 1-Norm, 2-Norm and infinity Norm of a matrix were executed successfully.




