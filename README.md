# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
	1. Get the input matrix using np.array()   
   	2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
```
## Program:
```Python
# Register No: 212224230144
# Developed By: LUKESH M

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

## 2-Norm of a Matrix
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
![ex 07 shot](https://github.com/user-attachments/assets/b16562fa-5fa5-46b5-b94c-622eda554032)


### 2-Norm of a Matrix

![ex 07 shot 1](https://github.com/user-attachments/assets/146342d0-5266-483d-a332-9051f8e5a81a)

### Infinity Norm of a Matrix
![ex 07 shot 2](https://github.com/user-attachments/assets/287f2dd2-02d3-475e-b80d-75d041f0dc3c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
