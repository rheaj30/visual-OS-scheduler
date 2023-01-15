# visual-OS-scheduler
I have used python as my programming language for this project.

It is required to implement an OS scheduler using different scheduling algorithms. The work is divided into two modules: 
•	“Process Generator”: generates the processes to bescheduled. 
•	“Scheduler”: produces the schedules based on the chosen algorithm and demonstrates these schedules by visualgraphs. 
Process Generator Module  
Each process has a set of parameters. Each parameter is generated randomly following a certain distribution as indicated: 
1.	Arrival Time : follows Normal distribution 
2.	Burst Time : follows Normal distribution 
3.	Priority : follows Poisson distribution  
Scheduler Module  
This module is responsible for generating a schedule for the current processes in the system to specify the CPU usage by these processes. 
You are required to implement 3 scheduling algorithms: 
1. Non-Preemptive Highest Priority First.(HPF) 
2. First Come First Served. (FCFS) 
3. Round Robin with fixed time quantum.(RR) 
4. Preemptive Shortest Remaining Time Next.(SRTN) 
 Final output-
•	A visual graph that shows the generated schedule. 
