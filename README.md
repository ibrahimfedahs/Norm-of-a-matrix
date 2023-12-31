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
# Register No:
# Developed By:
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
norm_of_matrix='{:.2f}'.format(ans)
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
![WhatsApp Image 2024-01-01 at 05 18 41_e31087cb](https://github.com/ibrahimfedahs/Norm-of-a-matrix/assets/150319493/3e49123e-20b7-4802-bbe5-cc1aee209762)


### 2-Norm of a Matrix
![WhatsApp Image 2024-01-01 at 05 19 08_ed5e7ca8](https://github.com/ibrahimfedahs/Norm-of-a-matrix/assets/150319493/45d4ac6c-2006-46df-b7d0-80ec378abc6f)


### Infinity Norm of a Matrix
![WhatsApp Image 2024-01-01 at 05 19 38_10403026](https://github.com/ibrahimfedahs/Norm-of-a-matrix/assets/150319493/a861b70a-ee64-4262-8395-92e84a5299ab)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
