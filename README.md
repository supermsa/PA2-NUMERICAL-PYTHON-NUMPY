**Michelle Sophia A. Abamonga** <br>
2-ECEB <br>
PA 2 - NUMERICAL PYTHON (NUMPY)

###### This repository contains Python scripts designed to address a range of programming problems in ECE2112. The focus is on array creation and the utilization of the NumPy library for numerical analysis. Presented below are the functions used in the specific Python exercise along its description and output.

## NORMALIZATION PROBLEM

#### Function: np.random.rand(5, 5)
Description: To create a randomized 5x5 ndarray <br>
Ouput: array([[0.26256697, 0.09802344, 0.33544294, 0.58002692, 0.41463787], <br>
       [0.78449554, 0.74121957, 0.27853559, 0.8312426 , 0.19848271], <br>
       [0.74820316, 0.05998456, 0.7437726 , 0.6306434 , 0.31057244], <br>
       [0.99652952, 0.48539258, 0.72587531, 0.57141517, 0.83280102], <br>
       [0.93472515, 0.14293943, 0.82180642, 0.90296696, 0.07540151]]) <br>

#### Function: np.mean()
Description: To calculate mean <br>
Output: 0.540308135324447 <br>


#### Function: np.std()
Description: To calculate the standard deviation <br>
Output: 0.2933152188247287 <br>

#### Function: np.std()
Description: To normalize variable with the given formula: Z = (X - mean) / std <br>
Output: array([[-0.94690335, -1.50788184, -0.69844721,  0.13541332, -0.42844783], <br>
       [ 0.83250848,  0.68496763, -0.8924615 ,  0.9918833 , -1.1653859 ], <br>
       [ 0.70877682, -1.63756787,  0.6936717 ,  0.30798014, -0.78323824], <br>
       [ 1.55539624, -0.18722368,  0.63265442,  0.10605325,  0.99719642], <br>
       [ 1.34468651, -1.35474971,  0.95971249,  1.23641325, -1.58500684]]) <br>

       
#### Function: np.save("X_normalized.npy", X_normalized)
Description: To save the normalized ndarray as X_normalized.npy <br>
Output: X_normalized.npy <br>

## NORMALIZATION PROBLEM

#### Function: np.arange(1, 101)**2
Description: To create an array of integers from 1 to 100, squaring each integer. <br>
Output: array([    1,     4,     9,    16,    25,    36,    49,    64,    81,
         100,   121,   144,   169,   196,   225,   256,   289,   324,
         361,   400,   441,   484,   529,   576,   625,   676,   729,
         784,   841,   900,   961,  1024,  1089,  1156,  1225,  1296,
        1369,  1444,  1521,  1600,  1681,  1764,  1849,  1936,  2025,
        2116,  2209,  2304,  2401,  2500,  2601,  2704,  2809,  2916,
        3025,  3136,  3249,  3364,  3481,  3600,  3721,  3844,  3969,
        4096,  4225,  4356,  4489,  4624,  4761,  4900,  5041,  5184,
        5329,  5476,  5625,  5776,  5929,  6084,  6241,  6400,  6561,
        6724,  6889,  7056,  7225,  7396,  7569,  7744,  7921,  8100,
        8281,  8464,  8649,  8836,  9025,  9216,  9409,  9604,  9801,
       10000])

#### Function: A.reshape(10, 10)
Description: To reshape array A in a 10x10 dimesion. <br>
Output: array([[    1,     4,     9,    16,    25,    36,    49,    64,    81,
          100], <br>
       [  121,   144,   169,   196,   225,   256,   289,   324,   361,
          400], <br>
       [  441,   484,   529,   576,   625,   676,   729,   784,   841,
          900], <br>
       [  961,  1024,  1089,  1156,  1225,  1296,  1369,  1444,  1521,
         1600], <br>
       [ 1681,  1764,  1849,  1936,  2025,  2116,  2209,  2304,  2401,
         2500], <br>
       [ 2601,  2704,  2809,  2916,  3025,  3136,  3249,  3364,  3481,
         3600], <br>
       [ 3721,  3844,  3969,  4096,  4225,  4356,  4489,  4624,  4761,
         4900], <br>
       [ 5041,  5184,  5329,  5476,  5625,  5776,  5929,  6084,  6241,
         6400], <br>
       [ 6561,  6724,  6889,  7056,  7225,  7396,  7569,  7744,  7921,
         8100], <br>
       [ 8281,  8464,  8649,  8836,  9025,  9216,  9409,  9604,  9801,
        10000]]) <br>

#### Function: A[A % 3 == 0]
Description: To determine the elements in array that are divisible by 3 <br>
Output: array([   9,   36,   81,  144,  225,  324,  441,  576,  729,  900, 1089,
       1296, 1521, 1764, 2025, 2304, 2601, 2916, 3249, 3600, 3969, 4356,
       4761, 5184, 5625, 6084, 6561, 7056, 7569, 8100, 8649, 9216, 9801])

#### Function: np.save('div_by_3.npy', div_by_3)
Description: To save the normalized ndarray as div_by_3.npy <br>
Output: div_by_3.npy <br>
