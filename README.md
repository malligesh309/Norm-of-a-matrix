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
# Register No:23002936
# Developed By:Malligesh
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
normmat="{:.2f}".format(ans)
print(normmat)
```



# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
normmat="{:.2f}".format(ans)
print(normmat)
```



# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
normmat="{:.2f}".format(ans)
print(normmat)
```






## Output:
### 1-Norm of a Matrix
![output](/Screenshot%20(26).png)


### 2-Norm of a Matrix
![output](/Screenshot%20(27).png)

### Infinity Norm of a Matrix
![output](/Screenshot%20(28).png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
