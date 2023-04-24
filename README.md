# OSProject

Overview
This program simulates Round Robin CPU scheduling algorithm. It takes a file containing process information as input and outputs the performance evaluation criteria of the algorithm such as CPU utilization, throughput, average waiting time, average turnaround time, and context switches.

Dependencies
This program uses Python 3.

Usage
To use this program, you need to create a file containing process information in the following format:

pid arrival_time service_time
pid arrival_time service_time
pid arrival_time service_time
...


Where pid is the process ID, arrival_time is the time when the process arrives, and service_time is the time required to complete the process.

After creating the process file, run the program by executing the following command:

python round_robin_scheduling.py process_file time_quantum

Where process_file is the path to the file containing process information and time_quantum is the time quantum for the Round Robin algorithm.

Output
The program outputs the following performance evaluation criteria:

CPU Utilization: the percentage of time the CPU is busy.
Throughput: the number of processes completed per unit time.
Average Waiting Time: the average time a process spends waiting in the ready queue.
Average Turnaround Time: the average time a process takes to complete execution from the time of arrival.
Context Switches: the number of times the CPU switches from one process to another.

Code Structure
The code consists of three main parts:

The Process class which stores information about each process.
The read_process_file function which reads the process file and returns a list of processes.
The round_robin_scheduling function which implements the Round Robin scheduling algorithm and calculates the performance evaluation criteria.

License
This program is licensed under the MIT License.
