Day 02 – Linux Architecture, Processes, and systemd

The core components of Linux (kernel, user space, init/systemd)
Linux is an Operating System introduced by Linus Torvalds, is important in Devops as more than 90% of apps are built and running in devops

COMPONENTS OF LINUX
1. Kernal- Acts as a bridge between hardware and software as Kernal helps an application to communicate with Hardware through Shell commands

2. User Space - refers to various programms that the OS uses to interact with Kernal

3. init/system d - init or system d is the 1st program/process run by Keranl immediately after system boots up. The process ID of the same is PID-01


How processes are created and managed
Processes in Linux are started as the system is booted forming a hierarchial tree structure with the init process being the 1st procss to get started. THere are various types of processes ike 'running', 'sleeping', 'zombie', etc.

Processes can be managed with the commans like 'top', 'htop', 'ps', 'kill'.

What systemd does and why it matters
systemd is the 1st process which runs in Linux as soon as the system boots up. Systemd has the process ID- 1 (PID-1)
It helps the system to boot up effeciently and helps o run other processes as well.


