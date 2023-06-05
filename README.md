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

'''
devloped by:kathiravan
registernumber: 21222223063
'''

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: kathiravan
RegisterNumber: 21222223063
'''


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: kathiravan
RegisterNumber: 21222223063
'''


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>![2023-06-05 (4)](https://github.com/kathiravan13/Norm-of-a-matrix/assets/119831303/7949f393-8e81-4fe3-8931-fed876b796ab)

<br>
<br>

### 2-Norm of a Matrix
![2023-06-05 (3)](https://github.com/kathiravan13/Norm-of-a-matrix/assets/119831303/8dbad2e8-1d06-4745-b328-cb6b3600c515)

<br>
<br>

### Infinity Norm of a Matrix

![2023-06-05 (2)](https://github.com/kathiravan13/Norm-of-a-matrix/assets/119831303/2bf763e0-f645-47cd-8c5c-6b3814525101)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
