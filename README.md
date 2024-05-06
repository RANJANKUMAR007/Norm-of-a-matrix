# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# step 1
 Get the input matrix using np.array()   
# step 2
 Find the 2-norm of the matrix using np.linalg.norm()
# step 3
 Print the norm of the matrix in two decimal places.
# step 5
End of the program
## Program:
```Python
# Register No:RANJAN KUMAR G
# Developed By:212223240138
# 1-Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: RANJAN KUMAR
RegisterNumber: 212223240138
'''
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix
```
DEVELOPED BY:RANJAN KUMAR G
REGISTER NO:212223240138
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2024-05-06 132536.png>)
### 2-Norm of a Matrix
![alt text](<Screenshot 2024-05-06 132548.png>)
### Infinity Norm of a Matrix
![alt text](<Screenshot 2024-05-06 132559.png>)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
