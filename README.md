- Start Date: 18-05-2021
- Proposed Project : Implementation of Matrix multiplication on FPGA


# Summary

Matrix multiplication is a mathematical operation that defines the product of two matrices. It's defined as

C(m, n) = A(m, k) * B(k, n)



It is considered the most computationally demanding kernel operation, used in many modern applications, such as in image processing or machine learning systems.  
For its need of billions of multiplication and addition operations. Thus, a highly competitive system of these systems requires a fast and efficient matrix multiplier as the core computation engine that uses the FPGA as a accelerator.

In our project, we will explain how to implement a high performance matrix multiplication on Vivado HLS using Xilinix and compare its performance with the one where the CPU alone is used. 

to acomplish that we will adopt the following approach:

- Create the matrix multiplication IP in vitis /cpp code (Task 1)
- Complete block design in vivado (Task 2)
- Synthesize the overlays (Task 3)
- Compare FPGA vs CPU (HW vs SW) performance (in function of matrix size) in the Jupyter notebook (Task 4)


# Estimated time
we will split the tasks between us so that we can finish the project in the estimated time of 39 hours .

| Tasks         | Estimated time (h) |
| ------------- | ------------------ |
| Task 1        |     10             |
| Task 2        |     15             |
| Task 3        |     8              |
| Task 4        |     6              |


# Required Hardware 
- PYNQ-Z2 development board 
- USB data cable
-  network cable
-  SD card

