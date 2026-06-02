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
# Register No:25011147
# Developed By:JITHESH PRASAD
```
```
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```


## Output:
### 1-Norm of a Matrix
<img width="1241" height="1755" alt="CODE_page-0001" src="https://github.com/user-attachments/assets/b2fac7d5-b44f-46ae-ac61-375c0baa7305" />

### 2-Norm of a Matrix
<img width="1241" height="1755" alt="CODE_page-0002" src="https://github.com/user-attachments/assets/4fc03a6d-8da8-4581-845f-0410fe70c900" />

### Infinity Norm of a Matrix
<img width="1241" height="1755" alt="CODE_page-0003" src="https://github.com/user-attachments/assets/fff72528-7a92-40a0-bea1-2cf66db3987d" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
