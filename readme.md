Operating Systems Coursework Archive (2024, 2nd Year)

This repository serves as a structured archive of the Operating Systems (OS) coursework carried out in the 2nd year, 2nd semester (Fall 2024) at Dankook University.

It contains my submitted assignments, projects, and reports based on original materials provided via the official course repository:

---
 Original Course Repository (GitHub)

  Each subdirectory contains:
  
  Source code (if applicable)
  
  README documentation for build & usage
  
  Summary of implementation/analysis
  
  Submission report (PDF/HWP format)

---
 Coursework Overview
  Category	Title	Description
  HW0	Git Usage & Group Setup	Team branch creation and Git operation practice
  HW1	Simple MyShell	Implementation of a basic Unix-like shell with process handling
  HW2	Multi-threaded Word Counter	Thread synchronization and alphabet statistics with pthreads
  Project 1	Simple Round-Robin Scheduler	Multi-process scheduling simulation using setitimer, msgq
  Project 2	Virtual Memory (Paging)	Demand paging, address translation, and page fault simulation
  Project 3	Ext2 File System Analysis	(Incomplete) File system metadata parsing, structure mapping
  Report	Large Number Arithmetic	Algorithm design for high-precision integer calculations

---
Directory Structure

  os-coursework-2024/
  ├── os_hw0/           # Git & Group setup
  ├── os_hw1/           # MyShell assignment (process-based shell)
  ├── os_hw2/           # Multi-threaded character counter
  ├── os_proj1/         # Simple RR scheduler with IPC
  ├── os_proj2/         # Virtual memory with demand paging
  ├── os_proj3/         # (Partial) ext2 file system analysis
  └── report_largeint/  # Standalone number calculation report

---
Learning Outcomes
  Through these assignments and projects, I explored core OS concepts in practice, including:
  
  Process & thread management
  
  System calls (fork, exec, wait, setitimer, msgsnd, etc.)
  
  Scheduling policies
  
  Thread synchronization with mutexes and condition variables
  
  Memory virtualization via paging and demand loading
  
  Filesystem structure analysis (ext2)
  
  Low-level debugging, Makefile-based build, profiling
  
  Each directory contains a self-contained explanation of what was implemented, what challenges were faced, and what was learned.

---
Notes
  All source files and reports were authored individually unless otherwise specified.
  
  Reports include both implementation analysis and performance observation.
  
  Original problem statements and codebases are available from the official repository:
  
  https://github.com/mobile-os-dku-cis-mse

---
License & Use
  The original coursework materials are under the ownership of the course instructor and department.
  My implementations are provided here for archival and educational purposes only.
  Do not copy or reuse the code without permission.
