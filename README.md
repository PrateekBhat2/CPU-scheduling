This project encompasses the implementation of various process scheduling algorithms. The scheduler is tasked with managing a predefined set of tasks, organizing them based on the selected scheduling algorithm. Each task is endowed with a priority and a CPU burst. The following scheduling algorithms will be executed:

First-come, first-served (FCFS): Arranges tasks in the order of their CPU request.
Shortest-job-first (SJF): Organizes tasks based on the length of their next CPU burst.
Priority scheduling: Schedules tasks according to their assigned priority.
Round-robin (RR) scheduling: Runs each task for a time quantum or the remainder of its CPU burst.
Priority with round-robin: Sequences tasks based on priority, utilizing round-robin scheduling for tasks with equal priority.
Task priorities are graded on a scale from 1 to 10, where a higher numeric value signifies a higher relative priority. In round-robin scheduling, the time quantum duration is set at 10 milliseconds.

Acknowledgment is given to the following references:

1) Geeks for Geeks
2) Java Point
