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
# Register No:23004042
# Developed By: thajesh k
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/119393424/216229377-0bf4cedc-b57a-4da6-8782-4e67b897ec1b.png)



### 2-Norm of a Matrix

![image](https://github.com/Thajesh2/Norm-of-a-matrix/assets/139841959/f710c7b8-3a88-4d86-9551-e15a9d071da1)


### Infinity Norm of a Matrix
![n3](https://user-images.githubusercontent.com/119393424/216229419-32dc6f34-99ee-4f0c-8e0c-a2dcfb67c784.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
