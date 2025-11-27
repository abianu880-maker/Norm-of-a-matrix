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
# Register No:Abilasha
# Developed By:25015770
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(f"{norm1:.2f}")



# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm2=np.linalg.norm(a,2)
print(f"{norm2:.2f}")





# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,ord=np.inf)
print(f"{norm:.2f}")




```
## Output:
### 1-Norm of a Matrix


<img width="1223" height="845" alt="Screenshot 2025-11-27 113020" src="https://github.com/user-attachments/assets/91d0aefb-7773-4eee-8aa2-1b20d012cc4a" />


### 2-Norm of a Matrix


<img width="1243" height="872" alt="Screenshot 2025-11-27 113030" src="https://github.com/user-attachments/assets/757688cb-98c8-4ae4-8725-9300eb0f8e1d" />

### Infinity Norm of a Matrix


<img width="1190" height="843" alt="Screenshot 2025-11-27 113041" src="https://github.com/user-attachments/assets/e81adc47-44e9-4b60-beaf-51c367e5c4a1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
