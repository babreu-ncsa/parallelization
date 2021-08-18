# parallelization
Series of examples on how to optmize/parallelize serial codes.

## [basics](./basics)
This folder has some basic exercises that optimize and parallelize very simple serial codes.
### 1. [matmul](./basics/matmul)
This is an example of a matrix multiplication code. It is currently offered in Fortran. It was tested with GCC 10.2.1 20201220.
#### [serial](./basics/matmul/serial)
Serial code in Fortran. Makefile is available for compilation with GCC. 
#### [compiler_opt](./basics/matmul/compiler_opt)
This folder contains the serial code and a supporting Python script and Jupyter notebook that compiles and runs the code with every single individual GCC optmization flag (listed [here](https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html)).
