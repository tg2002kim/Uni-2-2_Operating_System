# Operating Systems Coursework

This repository serves as a structured archive of the **Operating Systems (OS)** coursework completed during the **Fall 2024** semester (2nd year, 2nd semester) at Dankook University. It contains submitted assignments, projects, and reports based on original materials from the official course repository.

---

## Coursework Overview

| Category | Title | Description |
| :--- | :--- | :--- |
| HW0 | Git Usage & Group Setup | Practice with team branch creation and Git operations. |
| HW1 | Simple MyShell | Implementation of a basic Unix-like shell with process handling. |
| HW2 | Multi-threaded Word Counter | Thread synchronization and alphabet statistics using `pthreads`. |
| Project 1 | Simple Round-Robin Scheduler | Multi-process scheduling simulation using `setitimer` and `msgq` (message queue). |
| Project 2 | Virtual Memory (Paging) | Simulation of demand paging, address translation, and page fault handling. |
| Project 3 | Ext2 File System Analysis | A partial implementation of file system metadata parsing and structure mapping. |
| Report | Large Number Arithmetic | Algorithm design for high-precision integer calculations. |

---

## Directory Structure

This repository is organized as follows:

os-coursework-2024/
├── os_hw0/             # Git & Group setup
├── os_hw1/             # MyShell assignment (process-based shell)
├── os_hw2/             # Multi-threaded character counter
├── os_proj1/           # Simple RR scheduler with IPC
├── os_proj2/           # Virtual memory with demand paging
├── os_proj3/           # (Partial) ext2 file system analysis
└── report_largeint/    # Standalone number calculation report


Each subdirectory is a self-contained unit, containing the source code, a `README` for build/usage, a summary of implementation, and a submission report (in PDF/HWP format).

---

## Learning Outcomes

Through these assignments and projects, I gained practical experience with core OS concepts, including:
- **Process & Thread Management**: Using system calls like `fork`, `exec`, and `wait`.
- **Scheduling Policies**: Understanding and implementing scheduling algorithms.
- **Synchronization**: Using mutexes and condition variables for thread safety.
- **Memory Virtualization**: Simulating demand paging and address translation.
- **Filesystem Analysis**: Gaining insight into the structure of the **Ext2 file system**.
- **System-Level Programming**: Practicing `Makefile`-based builds, low-level debugging, and performance profiling.

---

## Notes

- All source files and reports were authored individually unless otherwise specified.
- The reports include both implementation analysis and performance observations.
- The original problem statements and codebases are available from the official course repository:
  - `https://github.com/mobile-os-dku-cis-mse`

---

## License & Use

- The original course materials are the property of the course instructor and department.
- My implementations are provided here for **archival and educational purposes only**.
- Do not copy or reuse the code without permission.
