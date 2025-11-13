# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	
1. **Start the program.**
2. **Import** the `numpy` library as `np`.
3. **Read the matrix** elements using `eval(input())` and store them in `mat`.
4. **Compute the 1-Norm** using `np.linalg.norm(mat, 1)`.
5. **Format the result** to two decimal places.
6. **Display the 1-Norm** of the matrix.
7. **End the program.**

---

## **Part B – L2-Norm of a Matrix**

1. **Start the program.**
2. **Import** the `numpy` library as `np`.
3. **Input the matrix** and store it in `mat`.
4. **Find the L2-Norm** using `np.linalg.norm(mat, 2)`.
5. **Round or format** the result to two decimal places.
6. **Print the L2-Norm** of the matrix.
7. **End the program.**

---

## **Part C – Infinity Norm of a Matrix**

1. **Start the program.**
2. **Import** the `numpy` library as `np`.
3. **Read the matrix** from user input.
4. **Calculate the Infinity Norm** using `np.linalg.norm(mat, np.inf)`.
5. **Format** the result to two decimal places.
6. **Display** the Infinity Norm of the matrix.
7. **End the program.**
## Program:
```Python
# Register No:212224230179
# Developed By:Nausheen Fathima A
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
<img width="810" height="284" alt="image" src="https://github.com/user-attachments/assets/cdccadb7-06d8-4926-9aa0-4e5accacb3d0" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="658" height="307" alt="image" src="https://github.com/user-attachments/assets/11a6c1c1-0e97-45f2-b9b3-3f2803b89335" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="718" height="265" alt="image" src="https://github.com/user-attachments/assets/998af494-61ac-4262-9edb-94abba1f5528" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
