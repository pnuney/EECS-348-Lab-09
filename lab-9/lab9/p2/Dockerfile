#Set the base image to use
FROM gcc:latest

#copy the C program into the container
COPY CProgram2.c .

#Compile the C program
RUN gcc -o CProgram2 CProgram2.c

#set the command to run when the container starts
CMD ["./CProgram2"]
