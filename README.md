# Operating System - Virtual Memory Simulator
**Introduction**

This project implements a simple virtual memory simulator with a translation mechanism from virtual addresses to physical addresses. The simulator uses a hierarchical page table structure to manage the mapping between virtual and physical memory addresses. It includes functionalities for reading from and writing to virtual memory addresses.

**Memory Constants (MemoryConstants.h)**

**Description**

The *MemoryConstants.h* file defines various constants related to the memory architecture, such as the size of the page, the number of frames, and the width of different address components.

**Physical Memory Implementation (PhysicalMemory.cpp)**

**Description**

The *PhysicalMemory.cpp* file provides an implementation of the physical memory, including read, write, evict, and restore operations. It uses a std::vector for representing RAM and an std::unordered_map for the swap file.

**Virtual Memory Implementation (VirtualMemory.cpp)**

**Description**

The *VirtualMemory.cpp* file implements the translation mechanism from virtual addresses to physical addresses. It uses a hierarchical page table structure and includes functions for initializing, reading, and writing to virtual memory.

