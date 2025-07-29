⚙️ CPU Scheduling Algorithms
CPU Scheduling is the strategy used by operating systems to determine the order in which processes are executed by the CPU. The main goals are:

✅ Maximize CPU utilization

⏳ Minimize waiting time

⚖️ Ensure fair resource allocation

🧠 Common Scheduling Algorithms
1. 🕐 First-Come, First-Served (FCFS)
Non-preemptive algorithm

Processes are executed in the order they arrive

✅ Simple to implement

⚠️ May cause convoy effect — long processes delay short ones

2. 📉 Shortest Job First (SJF)
Selects the process with the shortest burst time

Can be preemptive (Shortest Remaining Time First) or non-preemptive

✅ Minimizes average waiting time

⚠️ Requires prior knowledge of process execution time

3. 🔁 Round Robin (RR)
Each process gets a fixed time quantum

Preemptive: CPU switches after time slice ends

✅ Ensures fairness, good for time-sharing systems

⚠️ Performance depends on the chosen quantum size

4. ⭐ Priority Scheduling
Each process has a priority level

CPU selects process with the highest priority

Can be preemptive or non-preemptive

⚠️ May lead to starvation for low-priority processes

➕ Solved with aging (gradually increasing waiting process priority)

