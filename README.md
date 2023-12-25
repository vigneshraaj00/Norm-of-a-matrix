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
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```



# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: pavithra p
RegisterNumber: 23007232
'''
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```

# Infinity Norm of a Matrix
```
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/23007232/Norm-of-a-matrix/assets/139115574/86488adf-f4f8-40b3-88cb-8d220f30b863)

### 2-Norm of a Matrix
![image](https://github.com/23007232/Norm-of-a-matrix/assets/139115574/327adf0a-df3a-4003-9cf7-2151b6db27dc)

### Infinity Norm of a Matrix
![image](https://github.com/23007232/Norm-of-a-matrix/assets/139115574/ccef6b7e-966e-413c-a2cc-0b7a0a6829b3)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
