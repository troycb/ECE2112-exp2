# ECE2112 Experiment 2
Experiment 2 contains two problems for the student to identify the codes and functions in the Numpy library and apply and use them in creating a Python program using the said library.

## Normalization Problem
The problem asks to normalize a random 5x5 array using the equation below.

![image](https://github.com/user-attachments/assets/beb635a4-b2e6-40a8-a169-8fbdd22b6e28)

It is done by storing the random array in variable X and then getting the normalized array by subtracting the obtained mean of the array from **np.mean(X)** from the array and then dividing its difference by the obtained standard deviation from **np.std(X)**. The normalized array is stored in the _X_normalized.npy_ file and uploaded to this repository along with the Jupyter Notebook file.

![image](https://github.com/user-attachments/assets/efb52547-e866-42ef-a235-bb1c29b538f3)


## Divisible By 3 Problem
The problem asks to create an array, a, containing the square values of the first 100 positive integers and then get the values in the array divisible by 3.

It is done by making an array using **np.arange(1,101,1)**, with a start set to 1, the end set to 101 due to Python's use of zero-based indexing, and the interval set to a single step. The array is then resized from 1x100 to 10x10 using **a.resize(10,10)**, and its values are squared using **np.square(a)** and assigned to a new variable. The values divisible by three are obtained through boolean indexing, where it will get the values that will satisfy the condition where the modulo of that value is equal to zero by creating the said condition and filtering the array that satisfies it. The values are stored in the _div_by_3.npy_ file and also uploaded in this repository.

![image](https://github.com/user-attachments/assets/9b029b4f-0d3c-4d32-897e-039c0fff8ea0)

