# Parallel-Computing-Shearsort
A small exercise in Parallel Computing to implement Shearsort using OddEven Sort 

Input: .dat file containing rows of information about Cuboids along with their serial number
Output: .dat file containing the Sorted serial numbers list of the Cuboids using a Volume Comparator.

The Algorithm uses a number of Processes in parallel using the MPI multi processing API
to perform ShearSort and in each iteration to also use OddEvenSort to sort the rows and columns efficiently. 
