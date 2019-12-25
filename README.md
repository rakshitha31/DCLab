# DC Lab
Open MP execution
gcc -fopenmp file_name.c (append -lm for q5 and -lgd for 6th)
./a.out

MPI execution
mpicc file_name.c
mpirun -np (number_of_processes) ./a.out
