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
# Register No: 212223110023
# Developed By: KISHORE NARAYANAN S R
# 1-Norm of a Matrix:
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(two_matrix))

# 2-Norm of a Matrix:
# Register No: 212223110023
# Developed By: KISHORE NARAYANAN S R
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))

# Infinity Norm of a Matrix:
# Register No: 212223110023
# Developed By: KISHORE NARAYANAN S R
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(two_matrix))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-20 182527](https://github.com/KISHORENARAYANANSR/Norm-of-a-matrix/assets/148202102/2fb680b7-3f12-4b73-8487-e757b4b436ac)


### 2-Norm of a Matrix
![Screenshot 2024-04-20 182540](https://github.com/KISHORENARAYANANSR/Norm-of-a-matrix/assets/148202102/abc60794-dbb1-4c26-b5d3-f6096f75da42)


### Infinity Norm of a Matrix
![Screenshot 2024-04-20 182554](https://github.com/KISHORENARAYANANSR/Norm-of-a-matrix/assets/148202102/4d04d8fd-f2e5-4427-9f65-97a7e9b6060d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
