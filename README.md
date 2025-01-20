# Week 2 - Buffer Overflow - 64Bit

For this assignment, you are going to perform a ret2shellcode on a 64 bit binary. There are a few things that you need to do in order to be successful.

1. Create shellcode (either yourself or through pwntools) that will open a shell or cat `/flag`
2. Put the shellcode somewhere on the stack. 
3. Overflow the buffer
4. Jump to shellcode

The following has been given to you:
- The binary (also on pwn.college)
- A template for you to use (this can be easily regenerated via `pwn template /path/to/binary > solve.py`)
- A test flag if you want to run it through Github CI/CD (NOTE: this is not guarenteed to work) 

Use this repository to submit your code. After you are finished submit to ELMS a document answering the following questions. 

1. What part of the code was vulnerable?
2. Why is it exploitable?
3. Name 2 ways that you would mitigate this exploit and why it prevent it from working. 
4. Provide any sources you used to help you learn. 

**Make sure to submit your code on Github Classroom, submit your flag on pwn.college, and submit your writeup on ELMS**


