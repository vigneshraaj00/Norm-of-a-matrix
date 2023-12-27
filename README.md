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
# Register No:23005346
# Developed By:vignesh raaj s
# 1-Norm of a Matrix
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```




# 2-Norm of a Matrix
```
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```

# 3-Infinity Norm of a Matrix
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
![Screenshot 2023-12-27 115129](https://github.com/vigneshraaj00/Norm-of-a-matrix/assets/138849113/25f880ac-f702-4f93-8905-e142d3023711)


### 2-Norm of a Matrix
![Screenshot 2023-12-27 115141](https://github.com/vigneshraaj00/Norm-of-a-matrix/assets/138849113/f7f91ae8-c2d9-4296-bacc-a0266e05cceb)


### Infinity Norm of a Matrix
![Screenshot 2023-12-27 115148](https://github.com/vigneshraaj00/Norm-of-a-matrix/assets/138849113/5f0b284d-6017-416b-8c4b-d94fa1eff5f8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
