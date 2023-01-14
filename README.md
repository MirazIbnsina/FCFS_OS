# FCFS_OS
Implementation FCFS in C code to find out Waiting Time (WT) and Turn Around Time (TAT)

# Interface
1. Click the file fcfs.c
2. Run any C compiler (Made by CodeBlocks)
3. Should works fine!


# Explanation
Inputs:
- Number of processes (P0, P1...)
- Brust time of each processes


Processing:

a. calcutaing values

   wt[i+1] = bt[i]+wt[i]
   
   tat[i] = wt[i] + bt[i]
   
b. Calculating average

   avg_wt+=wt[i]
   
   avg_tat+=tat[i]
    



# Contact
Any query or customize project?
- mirazibnsina@outlook.com
