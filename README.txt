*** CS566 Parallel Processing *** Assignment 4 ***

Name: Zohair Hashmi
UIN: 668913771
Date: 4/12/2024

System:
GPU NVIDA GeForce GTX 1050
Build cuda_12.4.r12.4/compiler.33961263_0
OS: Windows 11 Home 64-bit

* NOTE: Since my system supports CUDA programming with integrated NVIDIA GPU,
I have used the same for this assignment.

Steps to run the code:
1. Open the terminal
2. Navigate to the directory where the code is saved
3. Run the following commands:
    nvcc <input_file_name>.cu -o <output_file_name>
    ./<output_file_name>
*/

Experimental Results:
```
1. hello_skeleton.cu (Threads : 2 and Blocks : 2)

        Hello from thread 1 of block 0
        Hello from thread 1 of block 1
        Hello from thread 0 of block 0
        Hello from thread 0 of block 1

2. vector_add_skelleton.cu (Threads : 16 and Blocks : 256)

        A[0] = 0.001251
        B[0] = 0.563585
        C[0] = 0.564837

3. matrix_sums_skeleton.cu (Threads : 64 and Blocks : 256)

        row sums correct!
        column sums correct!

```
