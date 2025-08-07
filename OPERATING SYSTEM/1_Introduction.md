# OPERATING SYSTEM

*System s/w that acts as an intermediary b/w user & h/w.*   
*Provides an environment, where users can execute programs by hiding complexity*

---
**WHAT IF NO OS ?**  
-> Bulky Complex App (OS code too inside apps)  
-> Resource exploitation by 1 App (Dominant)  
-> No Memory Protection (Breach)

---
**FUNCTIONS/GOALS OF OS ?**  
-> Maximum CPU Utilization  
-> Avoid Process Starvation  
-> High Priority Job Execution  
-> Provides Interface,  
-> Arbitration,  
-> Abstraction,  
-> Isolation & Protection



# <center> TYPES

1. BATCH OS

2. MULTI-PROGRAMMING OS  
Multiple programs are loaded into memory,  
CPU switches between them to maximize CPU usage

3. MUTI-TASKING OS  
Allows a single user to run multiple tasks at the same time.

4. MUTLI-PROCESSING  
Uses multiple CPUs (or cores) to run multiple processes in parallel. 

| Feature          | **Multiprogramming**        | **Multitasking**                | **Multiprocessing**                 |
| ---------------- | --------------------------- | ------------------------------- | ----------------------------------- |
| CPUs             | 1                           | 1                               | More than 1                         |
| Execution        | One at a time (others wait) | Multiple tasks (fast switching) | True parallel execution             |
| Example OS       | Early UNIX, Batch systems   | Windows, Linux                  | Windows, macOS, Linux on multi-core |


5. REAL TIME OS  
An RTOS responds to inputs or events within a strict time limit (called deadlines).  
A Hard Real-Time System guarantees that critical tasks are completed within a strict deadline — if missed, it can cause catastrophic failure.  
A Soft Real-Time System tries to meet deadlines, but occasional delays are acceptable. It may degrade performance but won’t cause serious damage.
