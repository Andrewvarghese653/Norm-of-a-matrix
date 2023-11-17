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
# Register No: 212222103001
# Developed By: ANDREW VARGHESE VS
# 1-Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
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
<br>
<br>
<br>
<img width="842" alt="Screenshot 2023-11-17 at 9 15 43 PM" src="https://github.com/Andrewvarghese653/Norm-of-a-matrix/assets/145822115/50a5a7df-01b5-4927-ac76-6b89182fa5f4">


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="803" alt="Screenshot 2023-11-17 at 9 16 51 PM" src="https://github.com/Andrewvarghese653/Norm-of-a-matrix/assets/145822115/b9786ea1-e08f-4048-ab94-64b6ae1d65d0">


### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="787" alt="Screenshot 2023-11-17 at 9 18 14 PM" src="https://github.com/Andrewvarghese653/Norm-of-a-matrix/assets/145822115/74f36219-1264-44d0-8921-158b33122693">


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
