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
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
'''
Developed by: Jenittan jose j b
RegisterNumber: 212224240063
'''



# 2-Norm of a Matrix

'''
Developed by: Jenittan Jose J B
RegisterNumber: 212224240063
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
'''
Developed by: jenittan jose j b
RegisterNumber: 212224240063
'''



```
## Output:
### 1-Norm of a Matrix

![Screenshot 2025-04-22 220432](https://github.com/user-attachments/assets/8460d4ea-fe52-485e-82ae-5adde745a0e3)



### 2-Norm of a Matrix

![Screenshot 2025-04-22 220452](https://github.com/user-attachments/assets/e549af89-2300-439d-aca2-0812ff50b707)


### Infinity Norm of a Matrix

![Screenshot 2025-04-22 220518](https://github.com/user-attachments/assets/d9ce72b9-eeee-43e2-a26e-87bf93e2a8a9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
