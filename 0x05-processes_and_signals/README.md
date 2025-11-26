# 0x05-processes_and_signals

## Description
This project introduces Linux processes and signals. It covers the basics of managing process lifecycles, monitoring running processes, and using signals to control process behavior. By completing these tasks, learners gain practical experience in process management on the command line.

## Learning Objectives
- Understand what a process is in Linux
- Retrieve and display process IDs (PIDs)
- List running processes
- Use signals to stop, start, and control processes
- Write Bash scripts that interact with processes

## Requirements
- All scripts must start with `#!/usr/bin/env bash`
- The second line must be a comment describing the script
- Scripts must be executable
- Files must be named exactly as specified in each task

## Tasks
- **0-what-is-my-pid**: Display the PID of the script itself.
- **1-list_your_processes**: List currently running processes.
- **2-show_your_bash_pid**: Display the PID of the current Bash shell.
- **3-show_your_bash_pid_again**: Display the PID of Bash using `ps`.
- **4-to_infinity_and_beyond**: Create a script that runs an infinite loop.
- **5-dont_stop_me_now**: Stop a process using signals.
- **6-stop_me_if_you_can**: Kill a process by PID.
- **7-highlander**: Ensure only one instance of a script runs at a time.

## Usage
To run a script:
```bash
chmod +x 0-what-is-my-pid
./0-what-is-my-pid
