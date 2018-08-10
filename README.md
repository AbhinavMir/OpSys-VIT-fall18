# OpSys-VIT-fall18
Practice files for CSE2005,Operating System-VIT,Fall '18.

Projects:-
1. Write a boot loader - to load a particular OS say TinyOS/ KolibriOS image - code
to access from BIOS to loading the OS - involves little assembly code – may use
QEMU/virtual machines for emulation of hardware.

2. Recompile kernel with you own program for 'cat'. Your 'cat' should read and
display contents of file on screen, check for errors, do it for multiple files while
taking input via command line.

3. Create and execute a system call in user/privileged mode in ARM/X86 processor.
Make it part of the kernel.

4. Allocate/free memory to processes in whole pages, find max allocatable pages,
incorporate address translation into the program.

5. Create an interrupt to handle a system call and continue the previously running
process after servicing the interrupt.

6. Write a Disk driver for the SATA interface. Take care to check readiness of the
controller, locked buffer cache, accept interrupts from OS during the period,
interrupting the OS again once done and clearing buffers.

7. Demonstrate the use of locks in conjunction with the IDE driver.

8. Implement DMA access, measure times required for varying sizes of the files.
Compare the times taken for a conventional read write via a OS for the same files.

9. Create a simple context switching module that switches between processes taking
care of all issues. Switch from process kernel thread to scheduler thread and back.

10. Compare the task creation times. Execute a process and kernel thread, determine
the time taken to create and run the threads.

11. Write a program to put a process to sleep and then wake it up and then kill it
when completed.

12. Run an experiment to determine the context switch time from one process to
another and one kernel thread to another. Compare the findings.

13. Implement a Keyboard driver.

14. Compare the overhead of a system call with a procedure call. What is the cost of
a minimal system call?

15. Determine the latency of individual integer access times in main memory, L1
Cache and L2 Cache. Plot the results in log of memory accessed vs average latency.

16. Determine the file read time for sequential and random access based of varying
sizes of the files. Take care not to read from cached data - used the raw device
interface. Draw a graph log/log plot of size of file vs average per-block time.
