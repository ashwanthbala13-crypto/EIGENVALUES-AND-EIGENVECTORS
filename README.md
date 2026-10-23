# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
### Step 2: import numpy as np

A = np.array([[2, -3, 0], [2, -5, 0], [0, 0, 3]])
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print("Eigen values are {} and Eigen Vectors are {}".format(values, vectors))

## Program:<img width="1322" height="508" alt="Screenshot 2026-10-23 082113" src="https://github.com/user-attachments/assets/29325969-6627-4eb5-a24a-7d4385e01ea9" />


## Output:<img width="1331" height="215" alt="Screenshot 2026-10-23 082120" src="https://github.com/user-attachments/assets/c73f1b2b-3663-4ec9-8cf5-64e6d21e85c5" />

## Result:<img width="1321" height="791" alt="Screenshot 2026-10-23 082144" src="https://github.com/user-attachments/assets/8b31757f-f01f-4276-b691-b292335934b7" />

Thus the Eigenvalue and Eigenvector is successfully solved using python program
