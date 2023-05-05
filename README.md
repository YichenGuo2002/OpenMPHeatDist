 - Assignment Name: OpenMP Heat Distribution

 - Assignment Tech Stack: C, OpenMP

 - Description: C and OpenMP based parallel computing program that computed the heat distribution for each block. Input block size, rounds of calculation, and compare the speed of parallel and sequential program.

 - Code Cheatsheet:
 ```
sftp <id>@access1.cims.nyu.edu
put <file>
exit

ssh <id>@access1.cims.nyu.edu
ssh <id>@crunchy1.cims.nyu.edu
module load gcc-12.2

gcc -Wall -std=c99 -fopenmp -o filename filename.c -lm
./filename x y z k

 ```
