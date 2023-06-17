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
# Register No: 212222110009
# Developed By: Dhiyaneshwar P
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Dhiyaneshwar
RegisterNumber: 212222110009
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Dhiyaneshwar
RegisterNumber: 212222110009
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)



# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Dhiyaneshwar
RegisterNumber: 212222110009
'''
import numpy as np
mat=np.array(eval(input()))
soln=np.linalg.norm(mat,np.inf)
norm= "{:.2f}".format(soln)
print(norm)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Dhiyanesh24/Norm-of-a-matrix/assets/118362288/137b969d-5fc4-4a9a-a6b9-6b34074643f4)


### 2-Norm of a Matrix
![image](https://github.com/Dhiyanesh24/Norm-of-a-matrix/assets/118362288/9fd0e89a-727a-4b64-9d9b-887a2b219700)


### Infinity Norm of a Matrix
![image](https://github.com/Dhiyanesh24/Norm-of-a-matrix/assets/118362288/08b5a2b7-8517-4394-a91d-8e93e42080f0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
