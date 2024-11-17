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
# Register No:212223230119
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
![image](https://github.com/user-attachments/assets/a52a3c42-f8e0-4c8c-abf4-c08660489ca5)



### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/4c450921-5012-42f4-9297-718dc769af95)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/2f3966d3-b785-41d4-b355-788f1f712bbc)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
