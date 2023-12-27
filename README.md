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
# Developed By:thajesh k
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

![image](https://github.com/divyadharshiniddanbarasu/Norm-of-a-matrix/assets/139841959/d63d1269-33a1-49ce-9abe-0a453ba0ae48)


### 2-Norm of a Matrix
![image](https://github.com/divyadharshiniddanbarasu/Norm-of-a-matrix/assets/139841959/0e5403fb-818c-44c2-9cab-78e5f99c09df)


### Infinity Norm of a Matrix
![image](https://github.com/divyadharshiniddanbarasu/Norm-of-a-matrix/assets/139841959/22a964cf-7a1c-487f-8714-c716ff06cfe3)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
