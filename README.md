
# XV6

How to run Scheduling in XV6?

[Description](https://dortmoot.tistory.com/28)

1. booting - bootasm.S
2. Create first-userlevel Process - Main.c
3. First Process init proc strucutre and kernel stack - Userinit Function
4. Scheduling( if you don't change Round Robin )

<br/>
I discuss xv6 default option.

[Description](https://dortmoot.tistory.com/27)

 - XV6's isolation unit is process.
 - Kernel support isolation with user, kernel mode / address space /
   time-slicing thread.
 - This is why processes have own's process ( docker container or Linux
   Container is same )
 - Page table support process's address space with identity.

<br/>
If you use Thread concept, you have to use Pthread(Posix Thread)
