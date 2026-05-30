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
# Register No: 212225040026
# Developed By: Apshara Priyadharshini M
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm="{:.2f}".format(ans)
print(Norm)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm="{:.2f}".format(ans)
print(Norm)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm="{:.2f}".format(ans)
print(Norm)




```
## Output:
### 1-Norm of a Matrix
<br><img width="1240" height="344" alt="image" src="https://github.com/user-attachments/assets/5bf854df-f189-4581-a340-881b0cf6bb2e" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1237" height="391" alt="image" src="https://github.com/user-attachments/assets/a0181159-5cf2-4c2b-b5db-5ac079d9af19" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1233" height="342" alt="image" src="https://github.com/user-attachments/assets/bc58fa0a-e099-48e1-881f-500569a97d5e" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
