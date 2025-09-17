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

# Register No:212224230304
# Developed By:B.VIMALRAJ
# 1-Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)
```

# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)

```



# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)
```



```
## Output:
### 1-Norm of a Matrix

<img width="1204" height="802" alt="Screenshot 2025-09-17 114319" src="https://github.com/user-attachments/assets/c8af8b4a-a039-461e-94a4-0f0180ae0726" />
<img width="1280" height="369" alt="Screenshot 2025-09-17 114328" src="https://github.com/user-attachments/assets/e4a075ad-5c75-439f-8cac-7b5de3ea024a" />


### 2-Norm of a Matrix
<img width="1147" height="786" alt="Screenshot 2025-09-17 114335" src="https://github.com/user-attachments/assets/f5d6569a-1402-493f-9d03-ce9626dac44d" />


<img width="1278" height="431" alt="Screenshot 2025-09-17 114348" src="https://github.com/user-attachments/assets/cb2f5639-0907-4c09-832d-8559f76a493e" />


### Infinity Norm of a Matrix

<img width="1412" height="768" alt="Screenshot 2025-09-17 114354" src="https://github.com/user-attachments/assets/82772200-0084-459d-8cf2-c101fbc3f185" />


<img width="1278" height="349" alt="Screenshot 2025-09-17 114401" src="https://github.com/user-attachments/assets/ab309bee-f69a-47d5-a89c-0bff52583b09" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
