
# Process Scheduling Algorithms Simulation

CPU Scheduling is a process of determining which process will own a CPU for execution while another process is on hold. The main task of CPU scheduling is to make sure that whenever the CPU remains idle, the OS at least selects one of the processes available in the ready queue for execution.

Assuming processes are scheduled on a single CPU. The objective of the project is to simulate the following eight algorithms and observe their performance under various performance metrics.


- First Come First Serve
- Shortest Job First Preemptive
- Shortest Job First Non-Preemptive
- Priority Preemptive
- Priority Non-Preemptive
- Round Robin
- Multi-level Queue
- Multi-level Feedback Queue


Once the simulation is done each of the algorithms would be compared based on the following parameters:
- Average waiting time
- Average response time
- Average turnaround time
- Average completion time



## Run Locally

Clone the project

```bash
  git https://github.com/mkk96/Process-Scheduling-Algorithms-Simulation.git
```

Go to the project directory

```bash
  cd Process-Scheduling-Algorithms-Simulatio
```

Install dependencies

```bash
  sudo apt install g++
  sudo apt install python3-dev
  pip3 install matplotlib
```

Compile the Files

```bash
  g++ -I /usr/include/python3.8 mainCPP.cpp -o main
```

Run the Files

```bash
  ./main <inputFile.csv>
```

Graph will be store in Graph Folder

## Input File Structure

CSV file with each row having `PID,name,type,Priority,AT,BT`

eg.
```
  0,P1,C,67,22,1
  1,P2,C,71,9,45
  2,P3,C,26,12,2
```


## Tech Stack

**Algorithm Simulation:** C++

**Graph Generation:** Python, Matplotlib


## Author

- [@Mukul Kumar](https://github.com/mkk96)


## Feedback

If you have any feedback, please reach out to us at one.end4@gmail.com

