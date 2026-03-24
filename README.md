# CPU-Scheduler-Solver
**CPU Scheduler Solver** is a Python-based graphical simulation tool developed as part of an Operating Systems course by **Chirag Maloo (23BIT192)** and **Sumit Mali (23BIT193)**.  
The application provides an intuitive and visual platform to understand the behavior of various CPU scheduling algorithms by illustrating process execution, timing, and performance analysis.

---

## Overview

This simulator enables users to enter process parameters such as **Arrival Time (AT), Burst Time (BT), Priority**, and **Time Quantum** (for Round Robin scheduling).  
Based on the provided inputs, users can run different scheduling algorithms and observe their execution.

The system computes and presents key performance metrics, including:
- Completion Time (CT)
- Turnaround Time (TAT)
- Waiting Time (WT)

It also calculates average values for better comparison across algorithms. Additionally, a **Gantt chart** is generated to visually represent the execution sequence and CPU utilization over time.

---

## Features

- Interactive graphical interface built using QtPy
- Supports multiple CPU scheduling algorithms:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF – Non-Preemptive)
  - Shortest Remaining Time First (SRTF)
  - Priority Scheduling (Preemptive and Non-Preemptive)
  - Round Robin (with customizable time quantum)
- User-friendly input system for:
  - Arrival Time (AT)
  - Burst Time (BT)
  - Priority (for priority-based algorithms)
  - Time Quantum (for Round Robin)
- Displays a comprehensive table of all process-related metrics
- Automatically calculates:
  - Average Turnaround Time
  - Average Waiting Time
- Generates a Gantt chart using Matplotlib for clear visualization
- Designed for easy understanding and educational use

---

## Technologies Used

- Python 3
- QtPy (compatible with PyQt / PySide)
- Matplotlib

---

## Output

- Detailed tabular representation of scheduling results
- Gantt chart showing execution order and time allocation
- Average Turnaround Time and Waiting Time for performance comparison

---

## Authors

- Chirag Maloo (23BIT192)
- Sumit Mali (23BIT193)
