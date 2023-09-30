Walking through the Code
Begin by compiling the bitreverse.cu CUDA application for debugging by entering the following command at a shell prompt:

$ nvcc -g -G bitreverse.cu -o bitreverse
This command assumes that the source file name is bitreverse.cu and that no additional compiler flags are required for compilation. See also Debug Compilation

Start the CUDA debugger by entering the following command at a shell prompt:

$ cuda-gdb bitreverse