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
# Register No: 212224100059
# Developed By: Thamizharasi G
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

<img width="1239" height="347" alt="image" src="https://github.com/user-attachments/assets/f0e0cba8-75a7-4ae0-b944-21a24f9f61f6" />

<br>

### 2-Norm of a Matrix

<img width="1243" height="393" alt="image" src="https://github.com/user-attachments/assets/eaa786cb-8413-4bef-a67b-be880d640233" />

<br>

### Infinity Norm of a Matrix

<img width="1243" height="347" alt="image" src="https://github.com/user-attachments/assets/5c76335f-e266-4630-b853-f8b2cfbe115a" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
