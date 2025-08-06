OS Project 3: Simple File System (2024)

This repository contains the planning and partial implementation for a simple file system simulator, developed for the Operating Systems course (Fall 2024, 2nd year).


📌 Original Assignment:
mobile-os-dku-cis-mse/2024-os-proj3


📂 Project Objective
The goal of this project is to simulate a basic file system with support for:

File storage on a block-based storage device

Logical-to-physical address mapping

File metadata management (via i-nodes)

Basic file operations (mount, open, read, close)

Support for directory structures and human-readable file names

This project builds on the concepts from previous assignments (scheduling, virtual memory) and extends into file system architecture, including:

Disk partition structure: superblock, inode table, data blocks

File representation with inodes

Directory entries mapping file names to inode numbers

Logical block mapping to physical data blocks

🔧 Planned Features (Partial Implementation)
Mounting of a disk image (disk.img) with predefined structure

Superblock and inode table parsing

Read-only access to files in the root directory

Directory entry lookup for file name resolution

File content reading by logical block mapping


📁 File System Structure (as specified)
[disk.img]
├── Superblock
├── Inode Table (224 entries)
├── Data Blocks (4,088 blocks)
Superblock: Holds global FS metadata (block size, # of inodes, etc.)

Inode: Describes individual file metadata and data block pointers

Directory Entry: Maps file name to inode number


📑 Example Data Structures (from spec)
struct super_block { ... };
struct inode { ... };
struct dentry { ... };
struct blocks { unsigned char d[1024]; };
struct partition { ... };


⚠️ Current Status
This project was not fully completed due to time constraints.
However, the planning, structure analysis, and partial parsing logic (e.g., superblock, directory entry) were explored and documented.

Further implementation would include:

File descriptor management

Full file read logic

Optional: write support, buffer cache, multi-user simulation, and disk image creation tool


🧾 References
Project Specification: project3.pdf

Base repository: mobile-os-dku-cis-mse/2024-os-proj3