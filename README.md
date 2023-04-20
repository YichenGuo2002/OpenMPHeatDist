 - Assignment Name: OpenMP Heat Distribution

 - Assignment Tech Stack: C, OpenMP

 - Description: 

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