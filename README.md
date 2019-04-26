# Xv-6-trace
trace - A system call in Xv-6 which when enabled helps us to trace and print total number of system calls and all the system calls made by the program. Useful for debugging purposes. 

Input parameters : 0 and any non-zero element 
functionality : Any non zero input wil enable the tracing and will keep printing the system calls which will be made, 0 will disble monitoring

eg: trace(0) means disabled
    trace(8) means enabled

 
You need to make a C file (test.c)
add a system call 
change proc structure in proc.h
and enable monitoring from syscall.c


all 9 related files are in the master branch
