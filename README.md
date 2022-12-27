# C-code-project
This projects includeds the following questions

1. Write a C program that opens a file (with the open() system call)
and then calls fork() to create a new process. Can both the child
and parent access the file descriptor returned by open()? What
happens when they are writing to the file concurrently, i.e., at the
same time?

2. Write a program that calls fork() and then calls some form of
exec() to run the program /bin/ls. See if you can try all of the
variants of exec(), including (on Linux) execl(), execle(), execlp(),
execv(), execvp(), and execvpe(). Why do you think there are so
many variants of the same basic call?

3. Now write a program that uses wait() to wait for the child process
to finish in the parent.
What does wait() return? What happens if you use wait() in the child
(what it will return and why)? Now use waitpid() instead of wait().
When would waitpid() be useful?

4. Write a program using 2 threads that take from the user an array
of numbers and call a function to calculate the sum of this array plus
finding the maximum and minimum elements in the array.

5. Create 5 threads where each thread can call a function to fill an
array of 20 elements and at the end combine these 5 array to get
one array with 100 elements in order.
ex:
T1 will fill an array with numbers from 1 to 20
T2 will fill an array with numbers from 21 to 40
T3 will fill an array with numbers from 41 to 60
T4 will fill an array with numbers from 61 to 80
T5 will fill an array with numbers from 81 to 100
At the end get print one array from 1 to 100 in order plus that print
the array created by each thread
