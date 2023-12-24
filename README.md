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
# Register No:23005191
# Developed By:KARTHIKEYAN M
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
![image](https://github.com/karthik-2106/Norm-of-a-matrix/assets/150319557/be98bca9-6345-4f88-a596-8732a0c237e9)

### 2-Norm of a Matrix
![image](https://github.com/karthik-2106/Norm-of-a-matrix/assets/150319557/090f84b9-d389-42eb-83e9-b7538550d034)

### Infinity Norm of a Matrix
![image](https://github.com/karthik-2106/Norm-of-a-matrix/assets/150319557/39824aad-2a5e-424c-bb4d-51f655ebd2fa)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
