# AASTMT | College of Artificial Intelligence
## High Performance Computing ![](https://img.shields.io/badge/Semester-Fall--2024-red)
---
## This Course is Conducted By:
- _Prof. Dr. Yasser Hanafy_ yhanafy@aast.edu
- _Eng. Ahmed M. Elsayed_ compiler@aast.edu
- _Eng. Amira Abuelyazid_ 
- _Eng. Nagy K. Aly_ nagy@aast.edu

| # | Topic | Content |
| ------ | ------ | ------ |
| 1 | Basics | Write & compile codes, calculate runtime, Compiler Optimization |

## Usefull commands
| Info	| Command |
| ------ | ------ |
| compile code | gcc file.c -o file |
| submit sequential job | sbatch submit.seq "./out_file" |
| monitor jobs progress | watch -n 1 "squeue" |
| submit job and calculate time| sbatch submit.seq "time ./out_file" |
| submit job and profile cache hit/miss| sbatch submit.seq "perf stat -d ./out_file" |
| submit job with input from file| sbatch submit.seq "perf stat -d ./dot-product" "data_50000_5000" |
| compile code with pthread | gcc input_file.c -o out_file -lpthread |
| submit threaded job | sbatch submit.pthread "./out_file" |
| submit openmp job | sbatch submit.omp "./out_file" |
| compile cuda code | submit.nvcc input_file.cu -o out_file |
| submit cuda job | sbatch submit.gpu "./out_file" |
| compile mpi code | mpicc input_file.c -o out_file |
| submit mpi job | sbatch submit.mpi "./out_file" |
