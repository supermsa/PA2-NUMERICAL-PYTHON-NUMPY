**Michelle Sophia A. Abamonga** <br>
2-ECEB <br>
PA 2 - NUMERICAL PYTHON (NUMPY)

This repository contains Python scripts designed to address a range of programming problems in ECE2112. The focus is on array creation and the utilization of the NumPy library for numerical analysis. Presented below are the functions used in the specific Python exercise along its description and output.

## NORMALIZATION PROBLEM

#### Function: np.random.rand(5, 5)
Description: To create a randomized 5x5 ndarray <br>
Ouput: <br>
array([[0.26256697, 0.09802344, 0.33544294, 0.58002692, 0.41463787],
       [0.78449554, 0.74121957, 0.27853559, 0.8312426 , 0.19848271],
       [0.74820316, 0.05998456, 0.7437726 , 0.6306434 , 0.31057244],
       [0.99652952, 0.48539258, 0.72587531, 0.57141517, 0.83280102],
       [0.93472515, 0.14293943, 0.82180642, 0.90296696, 0.07540151]]) <br>

#### Function: np.mean()
Description: To calculate mean <br>
Output: <br>
0.540308135324447 <br>


#### Function: np.std()
Description: To calculate the standard deviation <br>
Output: <br>
0.2933152188247287 <br>

#### Function: np.std()
Description: To normalize variable with the given formula: Z = (X - mean) / std <br>
Output: <br>
array([[-0.94690335, -1.50788184, -0.69844721,  0.13541332, -0.42844783],
       [ 0.83250848,  0.68496763, -0.8924615 ,  0.9918833 , -1.1653859 ],
       [ 0.70877682, -1.63756787,  0.6936717 ,  0.30798014, -0.78323824],
       [ 1.55539624, -0.18722368,  0.63265442,  0.10605325,  0.99719642],
       [ 1.34468651, -1.35474971,  0.95971249,  1.23641325, -1.58500684]]) <br>

       
#### Function: np.save("X_normalized.npy", X_normalized)
Description: To save the normalized ndarray as X_normalized.npy <br>
Output: <br>
X_normalized.npy <br>
