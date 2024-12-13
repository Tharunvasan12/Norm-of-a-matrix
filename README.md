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
# Register No:Tharunish vasan
# Developed By:24001333
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
![Screenshot 2024-12-13 104333](https://github.com/user-attachments/assets/c1a98d88-e56f-4d35-9bad-72465be0842f)



### 2-Norm of a Matrix
![Screenshot 2024-12-13 104405](https://github.com/user-attachments/assets/916883a1-7b90-44f7-b9b7-887d938c3566)


### Infinity Norm of a Matrix
![Screenshot 2024-12-13 104429](https://github.com/user-attachments/assets/3a22675a-51fa-435a-9121-df1cbd06d8cb)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
