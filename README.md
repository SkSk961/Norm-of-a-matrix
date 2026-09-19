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


# 1-Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array (eval(input()))
result=np.linalg.norm(matrix,1)
print(result)
```



# 2-Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array (eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")
```




# Infinity Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array (eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(result)
```
## Output:
<img width="1036" height="280" alt="image" src="https://github.com/user-attachments/assets/987a2e84-75f6-4901-b5ed-3aed6a88871c" />
<img width="1007" height="335" alt="image" src="https://github.com/user-attachments/assets/3c6048bf-0462-4267-83cb-61e58c5327f9" />
<img width="967" height="290" alt="image" src="https://github.com/user-attachments/assets/fc7002db-460a-4781-978b-f874d863d255" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
