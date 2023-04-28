
# CPU SCHEDULING PROJECT SPRING 2023 M01 CSCI 330 Operating Systems

The Round Robin CPU Scheduling technique is used in this project to mimic how processes might run in an operating system.
## Project Description

Preemptive CPU scheduling algorithms like the Round Robin algorithm execute each process for a set amount of time. When this window has passed, the process is withdrawn from the ready queue and the subsequent process is run. The process is moved to the end of the ready queue and the following process is run if the time quantum for execution is not met. Until each procedure is finished, this process keeps going.

Process ID, Arrival Time, and Burst Time are the three columns in the CSV file from which this project extracts process data. The Round Robin algorithm's time quantum must be entered by the user. The Round Robin algorithm is then used to execute the processes, and the software reports the start time, finish time, and turnaround time for each process.

## How to Run
Follow these steps to run the project:

1. Make sure Python 3.6 or a later version is installed on your computer.
2. From this repository, get the `RoundRobin.py` and `RoundRobin.csv files`.
3. Open a terminal or command prompt, then go to the files' directory.
4. To launch the application, type python `RoundRobin.py`.
5. When asked, enter the time quantum.
6. The software will carry out the operations and output the outcomes to the 
terminal.

## Dependencies

Installing Python 3.6 or a later version is necessary for this project.


## CSV File Format

Three columns should be present in the CSV file:

1. Process ID (a numeric value)
2. Arrival Time (a numeric value)
3. Time Burst (an integer)

The columns reflect the properties of the processes, and each row represents a process. The column headings should be in the first row. For instance:

```python

Process ID, Arrival Time, Burst Time
1,0,6
2,3,2
3,5,1
4,9,7
```
## Author
This project was created by Kamran Adil and Mysura Reddy Kuchuru as part of the Operating Systems Course at the New York Institute of Technology.

