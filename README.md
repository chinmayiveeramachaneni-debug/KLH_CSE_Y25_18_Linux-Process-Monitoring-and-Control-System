# KLH_CSE_Y25_18_Linux-Process-Monitoring-and-Control-System

Linux Process Monitoring and Control System


Team Members:


Vennela - 2520030288


Chinmayi - 2520030144


Jahnavi - 2520030567


Supervisor:

DR.Y.Harika Devi


Abstract:


The Linux Process Monitoring and Control System is a system programming project designed to monitor and manage processes running in a Linux operating system. The project provides information about active processes, including their Process ID (PID), process name, CPU usage, memory usage, and current status.

The system uses Linux process management concepts and system calls such as fork(), exec(), wait(), kill(), and getpid() to create, execute, monitor, and control processes. Users can view the list of running processes and perform basic control operations such as terminating or stopping a selected process.

The project helps demonstrate important Operating System concepts including process creation, process states, process identification, process synchronization, and process control. It can be implemented using the C programming language in a Linux environment. The system provides a command-line interface, making it lightweight and easy to execute.

This project gives practical experience with Linux system programming and helps users understand how the operating system manages multiple processes efficiently.


Setup:


Requirements:

Ubuntu/Linux
GCC compiler
C programming

Commands:

sudo apt update
sudo apt install gcc
mkdir LinuxProcessMonitor
cd LinuxProcessMonitor
nano process_monitor.c
gcc process_monitor.c -o process_monitor
./process_monitor

Main system calls: fork(), exec(), wait(), kill(), getpid()

Execution Instructions


Open the Linux/Ubuntu terminal.

Navigate to the project folder.

Compile the C program:

gcc process_monitor.c -o process_monitor

Run the program:

./process_monitor

Select the required process monitoring or control option from the menu.

Current Phase Status:


Phase 1 – Development: Project setup and basic process monitoring functionality have been completed. Process identification and control features are currently being implemented and tested.
