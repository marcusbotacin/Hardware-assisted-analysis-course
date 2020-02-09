# Hardware-assisted-analysis-course
Additional Material for the Hardware-Assisted Binary and System Analysis course.

## Content

* Analysis Requirements 
    * Transparency
    * Performance 
    * Anti-Tampering
* Abstraction, Layers, Rings 
    * Kernel vs userland
    * Virtual vs Physical memory
    * Semantic Gap and Introspection
* Trusted Code Base (TCB) vs Development Effort (Lines of Code -- LoC)
* Technologies 
    * VT-X/SVM
        * Hypervisors
        * VM Control Structures
        * Hypercalls
        * Xen Dom0
        * VM-entry and VM-exits
        * Extended Page Tables
    * SMM
        * Addressing
        * SMIs
    * Management Engine
        * Rootkits and Defenses
    * Performance Counters
        * PEBS, LBR, BTS
        * Branch Types (far branches, indirect branches)
    * Enclaves (SGX and TrustZone)
        * Page Isolation
        * Recompilation 
    * DMA
        * Memory Protection
        * Memory Isolation
        * Memory Dumping
        * Fake NIC cards
        * GPU-DMA
    * Co-processors
        * Hardware Isolation
        * Passive Monitoring
        * Shared Buses
        * System On Chip (SOC)
* Techniques
    * Events
    * Callbacks
    * Fallbacks
    * Breakpoints
        * Software Breakpoints
        * Hardware Breakpoints
        * Watchpoints
        * Data Breakpoints
    * Exceptions
    * MMU Protection
        * W xor E policies
        * SMC code execution
        * Rop Attacks
    * Memory Dumps
        * Run and Dump
        * Dump on Write
        * Shadow Copies
    * Stepping
        * Single-Stepping
        * Step Into vs Step Over
        * Stepping using Overflow Exceptions
* Applications
    * Malware Analysis
    * Debugging
    * Policy Enforcement
    * Forensics
    * Attack Detection
    * CFI control
* Research Gaps
    * SGX Malware
        * Encrypted Downloader Example

## Organization

* **Theory**: Course text (In Portuguese).
* **Presentation**: Course slides.
* **Pratice**: Some basic exercises.
