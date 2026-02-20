# Operating Systems in 90 Days - Complete Roadmap for B.Tech CSE Students

## A Comprehensive, Structured, and Detailed Study Plan for Theory, Practical, and Interview Preparation

---

## Table of Contents

1. [Introduction and Overview](#introduction-and-overview)
2. [Monthly Breakdown Overview](#monthly-breakdown-overview)
3. [Week-by-Week Detailed Roadmap](#week-by-week-detailed-roadmap)
4. [Detailed Day-by-Day Plan (Days 1-90)](#detailed-day-by-day-plan-days-1-90)
5. [10 Most Important OS Diagrams to Master](#10-most-important-os-diagrams-to-master)
6. [25 Most Important OS Interview Questions](#25-most-important-os-interview-questions)
7. [20 Most Important GATE OS Topics](#20-most-important-gate-os-topics)
8. [Important Coding Problems](#important-coding-problems)
9. [Recommended Books and Free Resources](#recommended-books-and-free-resources)
10. [Weekly Revision Plan](#weekly-revision-plan)
11. [Mini Projects and Final Major Project](#mini-projects-and-final-major-project)
12. [Concept Clarity Checkpoints](#concept-clarity-checkpoints)
13. [Weekly Self-Tests](#weekly-self-tests)

---

## Introduction and Overview

### Purpose of This Roadmap

This comprehensive 90-day roadmap is designed to transform a B.Tech CSE student from an OS beginner to an advanced level learner who can:
- Understand core operating system concepts in depth
- Implement practical OS concepts through coding
- Excel in university examinations and GATE
- Perform confidently in technical interviews

### Prerequisites

- Basic knowledge of C programming
- Familiarity with data structures (processes, queues, linked lists)
- Understanding of computer architecture basics
- A Linux system or virtual machine (strongly recommended)

### What This Roadmap Covers

- **Theory**: Complete OS concepts from basics to advanced
- **Practical**: Hands-on coding, Linux commands, shell scripting
- **Interview Preparation**: Frequently asked questions, GATE topics
- **Visual Learning**: Important diagrams to practice and master

---

## Monthly Breakdown Overview

### Month 1: Foundations and Process Management (Days 1-30)
- Introduction to Operating Systems
- OS Structure and Services
- System Calls
- Process Management
- Thread Management
- CPU Scheduling Algorithms

### Month 2: Concurrency and Memory Management (Days 31-60)
- Process Synchronization
- Deadlocks
- Memory Management
- Paging and Segmentation
- Virtual Memory

### Month 3: Advanced Topics and Interview Prep (Days 61-90)
- File Systems
- Disk Scheduling
- I/O Systems
- Protection and Security
- Linux Internals
- Shell Scripting
- Interview Questions
- GATE Practice
- Final Project

---

## Week-by-Week Detailed Roadmap

### Month 1: Week 1-4 (Days 1-30)

#### Week 1: Introduction and OS Architecture (Days 1-7)
- **Focus**: Introduction to OS, OS services, system calls
- **Theory Goals**: Understand what OS is, its functions, types, and basic structure
- **Practical Goals**: Basic Linux commands, understanding system calls
- **GATE Focus**: OS definitions, types, functions

#### Week 2: Process Management (Days 8-14)
- **Focus**: Process concepts, PCB, process states, operations
- **Theory Goals**: Process life cycle, PCB structure, process creation
- **Practical Goals**: fork(), exec(), wait() system calls in C
- **GATE Focus**: Process control block, state diagram

#### Week 3: Thread Management and CPU Scheduling (Days 15-21)
- **Focus**: Threads vs processes, CPU scheduling algorithms
- **Theory Goals**: Multithreading, scheduling criteria, algorithm analysis
- **Practical Goals**: Implement scheduling algorithms in C
- **GATE Focus**: FCFS, SJF, RR, Priority scheduling calculations

#### Week 4: Process Synchronization (Days 22-30)
- **Focus**: Critical section, synchronization primitives
- **Theory Goals**: Race conditions, mutex, semaphores, monitors
- **Practical Goals**: Pthread programming, producer-consumer problem
- **GATE Focus**: Synchronization problems, deadlock conditions

### Month 2: Week 5-8 (Days 31-60)

#### Week 5: Deadlocks (Days 31-37)
- **Focus**: Deadlock characterization, prevention, avoidance, detection
- **Theory Goals**: Necessary conditions, resource allocation graph
- **Practical Goals**: Banker's algorithm implementation
- **GATE Focus**: Deadlock prevention vs avoidance, detection and recovery

#### Week 6: Memory Management (Days 38-44)
- **Focus**: Contiguous memory allocation, paging
- **Theory Goals**: Memory allocation methods, page tables, TLB
- **Practical Goals**: Memory allocation simulation
- **GATE Focus**: Fragmentation, paging calculations

#### Week 7: Virtual Memory (Days 45-51)
- **Focus**: Demand paging, page replacement algorithms
- **Theory Goals**: Page fault handling, working set, thrashing
- **Practical Goals**: LRU, FIFO, Optimal algorithm implementation
- **GATE Focus**: Page fault calculations, Belady's anomaly

#### Week 8: File Systems and I/O (Days 52-60)
- **Focus**: File concepts, directory structure, disk scheduling
- **Theory Goals**: File allocation methods, free space management
- **Practical Goals**: Simple file system implementation
- **GATE Focus**: FCFS, SCAN, C-SCAN calculations

### Month 3: Week 9-12 (Days 61-90)

#### Week 9: Protection and Security (Days 61-67)
- **Focus**: Access control, authentication, security models
- **Theory Goals**: Protection mechanisms, security policies
- **Practical Goals**: Linux file permissions, user management
- **GATE Focus**: Access matrix, security threats

#### Week 10: Linux Internals Basics (Days 68-74)
- **Focus**: Linux kernel, process scheduling, memory management
- **Theory Goals**: Kernel architecture, system startup
- **Practical Goals**: Linux command line, system monitoring
- **GATE Focus**: Linux vs other OS, process management in Linux

#### Week 11: Shell Scripting (Days 75-81)
- **Focus**: Bash scripting, automation
- **Theory Goals**: Scripting constructs, functions
- **Practical Goals**: Write scripts for OS monitoring
- **GATE Focus**: Shell basics (theoretical understanding)

#### Week 12: Interview and GATE Preparation (Days 82-90)
- **Focus**: Comprehensive revision, mock interviews
- **Theory Goals**: All topics revision
- **Practical Goals**: Final project completion
- **GATE Focus**: Previous year questions, important topics

---

## Detailed Day-by-Day Plan (Days 1-90)

### DAY 1: Introduction to Operating Systems - Basic Concepts

**Theory Learning Goals:**
- Define Operating System and explain its role
- Understand the history and evolution of OS
- Learn about different types of OS: Batch, Multiprogrammed, Time-sharing, Real-time, Distributed, Network
- Understand the bootstrap program and system boot process

**Concepts to Master:**
- What is an OS? Definition and purpose
- OS as Resource Manager
- OS as Extended Machine
- Layered architecture of OS
- Simple Batch System
- Multiprogramming concept

**Reading Material:**
- OS Chapter 1: Introduction (Silberschatz, Galvin, Gagne)
- TOC: Introduction section

**GATE Important Points:**
- OS definition and functions (1-2 marks)
- Types of OS (understand differences)

**Interview FAQ:**
- What is the purpose of an Operating System?
- What are the main functions of an OS?

**Daily Assignment:**
- Write a 200-word summary on "What is an Operating System?"
- Create a flowchart showing OS boot process

---

### DAY 2: Operating System Services and Structure

**Theory Learning Goals:**
- Understand the services provided by OS to users and processes
- Learn about system calls and their types
- Understand OS design and implementation approaches

**Concepts to Master:**
- User interface (CLI, GUI)
- Program execution
- I/O operations
- File system manipulation
- Communication
- Error detection
- Resource allocation
- Protection and security

**System Calls Overview:**
- Process control (fork, exec, wait, exit)
- File management (open, read, write, close)
- Device management (ioctl, read, write)
- Information maintenance (getpid, alarm, sleep)
- Communication (pipe, shmget, mmap)
- Protection (chmod, umask, chown)

**Practical Task:**
- Practice basic Linux commands: ls, cd, pwd, mkdir, rmdir, cp, mv, rm
- Explore /proc filesystem in Linux
- Use man pages to understand system calls

**GATE Important Points:**
- System call types and their purposes
- OS services understanding

**Interview FAQ:**
- What services does an OS provide?
- Difference between API and system call?

---

### DAY 3: Operating System Structure - Monolithic, Layered, Microkernel

**Theory Learning Goals:**
- Learn about different OS architectural approaches
- Understand the advantages and disadvantages of each structure

**Concepts to Master:**
- Monolithic Kernel Architecture
- Layered Architecture
- Microkernel Architecture
- Hybrid Architecture (Linux, Windows)
- Exokernel and Virtual Machines

**Reading Material:**
- Silberschatz Chapter 2: Operating System Structures

**Comparison Table to Create:**
```
| Feature     | Monolithic | Layered | Microkernel |
|-------------|------------|---------|-------------|
| Performance | High       | Medium  | Lower       |
| Size        | Large      | Medium  | Small       |
| Extensibility| Hard      | Medium  | Easy        |
| Reliability | Lower      | Higher  | Highest     |
| Examples    | Linux, Unix| Early OS| MINIX, QNX  |
```

**GATE Important Points:**
- Characteristics of each architecture
- Linux kernel architecture

**Interview FAQ:**
- What is a microkernel? Give examples
- Why is Linux a monolithic kernel?

---

### DAY 4: Practice Problems and Revision - Introduction

**Theory Revision Goals:**
- Review all concepts from Days 1-3
- Solve numerical problems

**GATE Practice Questions:**
1. Which of the following is NOT a function of an Operating System?
   a) Process Management b) Memory Management c) Compilation d) File Management
   
2. Which type of OS is designed for real-time applications?
   a) Batch OS b) Distributed OS c) Real-time OS d) Network OS

3. The main function of system calls is to:
   a) Provide interface between user program and OS
   b) Compile programs
   c) Connect hardware to software
   d) Manage memory

**Practical Assignment:**
- Write a C program that demonstrates the use of at least 3 system calls
- Document the system calls used and their purpose

**Self-Test Questions:**
- Define OS in your own words
- List 5 services provided by OS
- Explain the boot process

---

### DAY 5: Process Concept and Process Control Block

**Theory Learning Goals:**
- Understand what is a process
- Learn about Process Control Block (PCB)
- Understand different process states

**Concepts to Master:**
- Process vs Program
- Components of a process (Program code, Data, Stack, PCB)
- Process State Diagram: New, Ready, Running, Waiting, Terminated
- PCB Structure: Process state, Program counter, CPU registers, Memory management info, I/O status info, Accounting info

**Important Diagram to Draw:**
```
Process State Diagram:
[New] → [Ready] → [Running] → [Terminated]
              ↑          ↓
            [Waiting] ←──┘
```

**PCB Structure to Learn:**
```
PCB {
    Process ID
    Process State
    Program Counter
    CPU Registers
    Memory Limits
    List of Open Files
    Scheduling Information
    Memory Management Info
    I/O Status Info
    Accounting Information
}
```

**GATE Important Points:**
- PCB contents and purpose
- Process state transitions (2-3 marks)

**Interview FAQ:**
- What is the difference between a process and a program?
- What information is stored in PCB?

---

### DAY 6: Process Operations and Process Creation

**Theory Learning Goals:**
- Learn about process creation in Unix/Linux
- Understand parent-child relationship
- Learn about process termination

**Concepts to Master:**
- Process Creation using fork()
- exec() system call family
- wait() and waitpid()
- Process termination (exit)
- Zombie and Orphan processes

**Practical Coding Task:**
Write a C program demonstrating:
```
c
#include <stdio.h>
#include <unistd.h>
#include <sys/wait.h>

int main() {
    pid_t pid = fork();
    
    if (pid == 0) {
        // Child process
        printf("I am child process, PID = %d\n", getpid());
        printf("My parent's PID = %d\n", getppid());
        // execl example
        // execl("/bin/ls", "ls", "-l", NULL);
    } else if (pid > 0) {
        // Parent process
        printf("I am parent process, PID = %d\n", getpid());
        printf("My child's PID = %d\n", pid);
        wait(NULL); // Wait for child
        printf("Child terminated\n");
    } else {
        // Fork failed
        perror("fork failed");
    }
    
    return 0;
}
```

**GATE Important Points:**
- fork() system call behavior
- Difference between zombie and orphan processes

**Interview FAQ:**
- What happens when fork() is called?
- What is a zombie process? How to prevent it?

---

### DAY 7: Threads - Concepts and Types

**Theory Learning Goals:**
- Understand the concept of threads
- Learn about single-threaded vs multithreaded processes
- Understand user threads and kernel threads

**Concepts to Master:**
- Thread definition
- Thread vs Process
- Benefits of multithreading
- User-level threads
- Kernel-level threads
- Threading models: Many-to-One, One-to-One, Many-to-Many

**Important Diagram:**
```
Process with Single Thread:
┌─────────────────────────────────┐
│            Process              │
│  ┌───────────────────────────┐  │
│  │         Thread            │  │
│  │  Stack, Registers, PC    │  │
│  └───────────────────────────┘  │
│  Code, Data, Files              │
└─────────────────────────────────┘

Process with Multiple Threads:
┌─────────────────────────────────┐
│            Process              │
│  ┌─────┐ ┌─────┐ ┌─────┐       │
│  │ Th1 │ │ Th2 │ │ Th3 │       │
│  │Stack│ │Stack│ │Stack│       │
│  └─────┘ └─────┘ └─────┘       │
│  Code, Data, Files, Registers  │
└─────────────────────────────────┘
```

**Practical Task:**
Write a simple pthreads program:
```
c
#include <pthread.h>
#include <stdio.h>
#include <stdlib.h>

void* print_message(void* arg) {
    char* msg = (char*)arg;
    printf("%s\n", msg);
    return NULL;
}

int main() {
    pthread_t thread1, thread2;
    pthread_create(&thread1, NULL, print_message, "Thread 1");
    pthread_create(&thread2, NULL, print_message, "Thread 2");
    pthread_join(thread1, NULL);
    pthread_join(thread2, NULL);
    return 0;
}
```

**GATE Important Points:**
- Thread vs Process (comparison table)
- Different threading models

**Interview FAQ:**
- What is a thread? How is it different from a process?
- Why do we use multithreading?

---

### DAY 8: CPU Scheduling - Basic Concepts and Scheduling Criteria

**Theory Learning Goals:**
- Understand CPU scheduling problem
- Learn about CPU-I/O burst cycle
- Understand scheduling criteria

**Concepts to Master:**
- CPU Burst vs I/O Burst
- Preemptive vs Non-preemptive scheduling
- Scheduling Criteria:
  - CPU Utilization (throughput)
  - Throughput
  - Turnaround Time
  - Waiting Time
  - Response Time

**Formulas to Remember:**
- Turnaround Time = Completion Time - Arrival Time
- Waiting Time = Turnaround Time - Burst Time
- Response Time = First Response Time - Arrival Time

**GATE Important Points:**
- All scheduling criteria definitions
- Calculation of turnaround time, waiting time

**Interview FAQ:**
- What is CPU scheduling?
- What is the difference between preemptive and non-preemptive scheduling?

---

### DAY 9: CPU Scheduling Algorithms - FCFS and SJF

**Theory Learning Goals:**
- Learn First Come First Served (FCFS) scheduling
- Learn Shortest Job First (SJF) scheduling
- Understand advantages and disadvantages

**FCFS Algorithm:**
- Non-preemptive
- Simple queue-based approach
- Problem: Convoy effect

**SJF Algorithm:**
- Non-preemptive (simple SJF)
- Preemptive (Shortest Remaining Time First - SRTF)
- Optimal for minimum average waiting time
- Problem: Starvation, Long job may never execute

**Numerical Problem Solving:**

**Example 1 - FCFS:**
```
Process | Arrival Time | Burst Time
P1      | 0            | 10
P2      | 1            | 5
P3      | 2            | 8

Gantt Chart:
P1 | P1 | P1 | P1 | P1 | P1 | P1 | P1 | P1 | P1 | P2 | P2 | P2 | P2 | P2 | P3 | P3 | P3 | P3 | P3 | P3 | P3 | P3
0  1   2   3   4   5   6   7   8   9   10  11  12  13  14  15  16  17  18  19  20  21  22  23

Completion Time: P1=10, P2=15, P3=23
Turnaround Time: P1=10-0=10, P2=15-1=14, P3=23-2=21
Waiting Time: P1=10-10=0, P2=14-5=9, P3=21-8=13
Average Waiting Time = (0+9+13)/3 = 22/3 = 7.33
```

**Example 2 - SJF (Non-preemptive):**
```
Process | Arrival Time | Burst Time
P1      | 0            | 6
P2      | 1            | 8
P3      | 2            | 7
P4      | 3            | 3

At time 0: Only P1 available → Execute P1 (0-6)
At time 6: P2, P3, P4 available → Shortest is P4 → Execute P4 (6-9)
At time 9: P2, P3 available → Shortest is P3 → Execute P3 (9-16)
At time 16: P2 remaining → Execute P2 (16-24)

Calculate all metrics similarly
```

**GATE Important Points:**
- SJF gives minimum average waiting time
- Convoy effect in FCFS
- Starvation in SJF

---

### DAY 10: CPU Scheduling Algorithms - Priority and Round Robin

**Theory Learning Goals:**
- Learn Priority Scheduling
- Learn Round Robin (RR) Scheduling
- Understand real-world applications

**Priority Scheduling:**
- Preemptive and Non-preemptive
- Priority can be defined internally or externally
- Problem: Starvation (aging can solve this)

**Round Robin Scheduling:**
- Preemptive
- Time quantum/Time slice concept
- Performance depends on time quantum
- No starvation
- Good for time-sharing systems

**Important Formula for RR:**
- If time quantum = q, then maximum waiting time = (n-1) × q
- For large q → FCFS behavior
- For small q → High context switching overhead

**Numerical Problem - RR:**
```
Process | Arrival Time | Burst Time | Time Quantum = 2
P1      | 0            | 10         
P2      | 1            | 5          
P3      | 2            | 8          

Gantt Chart:
P1(0-2) | P2(2-4) | P3(4-6) | P1(6-8) | P3(8-10) | P2(10-12) | P3(12-14) | P1(14-16) | P3(16-18)

Calculate completion times, turnaround times, waiting times
```

**GATE Important Points:**
- RR is preemptive, no starvation
- Effect of time quantum on performance

---

### DAY 11: CPU Scheduling Algorithms - Multilevel Queue and Multilevel Feedback Queue

**Theory Learning Goals:**
- Learn advanced scheduling approaches
- Understand real-world scheduling in Linux/Windows

**Multilevel Queue Scheduling:**
- Multiple queues for different process types
- Each queue has its own scheduling algorithm
- Fixed priority between queues
- Problem: No movement between queues

**Multilevel Feedback Queue Scheduling:**
- Processes can move between queues
- Aging can be implemented
- More flexible
- Can approximate SJF

**Important Diagram:**
```
Multilevel Feedback Queue:
┌─────────────────────────────────────┐
│           Ready Queue               │
│  ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐   │
│  │ Q0  │→│ Q1  │→│ Q2  │→│ Q3  │   │
│  │ RR  │  │ RR  │  │ FCFS│  │ ... │   │
│  │ q=2 │  │ q=4 │  │     │  │     │
│  └─────┘ └─────┘ └─────┘ └─────┘   │
└─────────────────────────────────────┘
```

**Linux CFS (Completely Fair Scheduler):**
- Based on virtual runtime
- Uses red-black tree
- Proportional to nice value

**GATE Important Points:**
- Feedback queue solves starvation problem
- Comparison of scheduling algorithms

---

### DAY 12: Practice Problems - CPU Scheduling

**Problem Solving Session:**

**GATE Problems:**

1. **GATE 2019:** Consider a CPU scheduling algorithm with two queues:
   - Q1: Round Robin (time quantum = 5 ms)
   - Q2: FCFS
   
   All processes enter Q1 first. If a process exceeds time quantum in Q1, it moves to Q2. If a process in Q1 is preempted by higher priority process, it goes to end of Q1. Which of the following is TRUE?
   
   a) 5ms: P1 executes, remaining time=5ms → move to Q2
   b) 10ms: P2 executes for 5ms, remaining=0 → complete
   c) Continue...

2. **GATE 2018:** Three processes arrive at time 0 with burst times 10, 20, 30 ms. Using SJF, what is average waiting time?

3. **GATE 2017:** In a round robin scheduling with time quantum = 4 ms, what is average turnaround time?

**Practical Assignment:**
Implement FCFS, SJF, and RR scheduling in C:
- Take process details as input
- Calculate and display completion time, turnaround time, waiting time
- Calculate average waiting time

---

### DAY 13: Process Synchronization - Introduction and Critical Section Problem

**Theory Learning Goals:**
- Understand process synchronization problem
- Learn about critical section
- Understand requirements for a good synchronization solution

**Concepts to Master:**
- Race Condition
- Critical Section Problem
- Mutual Exclusion
- Progress
- Bounded Waiting

**Critical Section Structure:**
```
c
do {
    entry section      // Request for entry
    critical section   // The code that accesses shared resources
    exit section       // Signal exit
    remainder section  // Other code
} while (true);
```

**Requirements for Solution:**
1. Mutual Exclusion: Only one process in critical section at a time
2. Progress: If no process in critical section and some want to enter, decide who enters
3. Bounded Waiting: Limit on number of times other processes can enter after a process requests

**GATE Important Points:**
- Critical section problem definitions
- Three requirements of solution

**Interview FAQ:**
- What is a race condition?
- What are the requirements for a critical section solution?

---

### DAY 14: Synchronization Hardware and Software Solutions

**Theory Learning Goals:**
- Learn hardware-based synchronization
- Understand software algorithms for critical section

**Hardware Solutions:**
- Test and Set instruction
- Swap instruction
- Disabling interrupts

**Software Solutions:**
- Peterson's Algorithm (for 2 processes)
- Bakery Algorithm (for n processes)

**Peterson's Solution:**
```
c
// For process 0
do {
    flag[0] = true;
    turn = 1;
    while(flag[1] && turn == 1);
    critical section
    flag[0] = false;
    remainder section
} while(true);
```

**GATE Important Points:**
- Hardware solutions impact on OS
- Peterson's algorithm (must know for 2 processes)

**Practical Task:**
Write a C program demonstrating race condition and then solve it using mutex

---

### DAY 15: Mutex and Semaphores

**Theory Learning Goals:**
- Learn about mutex locks
- Understand counting semaphores and binary semaphores
- Learn semaphore implementation

**Mutex (Mutual Exclusion):**
- Binary semaphore (0 or 1)
- Used for mutual exclusion
- Only one process can acquire

**Semaphore:**
- Integer variable
- Two atomic operations: wait() and signal()
- Can be counting or binary

**Semaphore Operations:**
```
c
wait(S) {
    while(S <= 0);
    S--;
}

signal(S) {
    S++;
}
```

**Binary vs Counting Semaphore:**
- Binary: Only 0 or 1 values
- Counting: Can have values > 1 (representing resources)

**GATE Important Points:**
- Semaphore operations (wait and signal)
- Difference between mutex and semaphore

**Interview FAQ:**
- What is a semaphore? Types?
- Difference between semaphore and mutex?

---

### DAY 16: Classical Synchronization Problems - Producer Consumer

**Theory Learning Goals:**
- Understand producer-consumer problem
- Learn to implement using semaphores

**Problem Statement:**
- Producer produces items and puts in buffer
- Consumer removes items from buffer
- Buffer has finite capacity
- No overflow, no underflow

**Solution with Semaphores:**
```
c
// Shared variables
int mutex = 1;    // Binary semaphore for mutual exclusion
int empty = n;    // Counting semaphore for empty slots
int full = 0;    // Counting semaphore for filled slots

// Producer
wait(empty);
wait(mutex);
// Add item to buffer
signal(mutex);
signal(full);

// Consumer
wait(full);
wait(mutex);
// Remove item from buffer
signal(mutex);
signal(empty);
```

**GATE Important Points:**
- Why two semaphores (empty and full)?
- Buffer size considerations

**Practical Task:**
Implement producer-consumer problem using pthreads in C

---

### DAY 17: Classical Synchronization Problems - Readers Writers and Dining Philosophers

**Theory Learning Goals:**
- Understand readers-writers problem
- Understand dining philosophers problem

**Readers-Writers Problem:**
- Multiple readers can read simultaneously
- Writers need exclusive access
- Solution using semaphores

**Dining Philosophers Problem:**
- 5 philosophers, 5 forks
- Need 2 forks to eat
- Deadlock and starvation issues
- Solutions: Resource hierarchy, Arbitrator, Philosopher states

**Dining Philosophers Solution (Semaphore):**
```
c
semaphore fork[5] = {1,1,1,1,1};
semaphore mutex = 1;
int state[5];

void philosopher(int i) {
    while(true) {
        think();
        pickup(i);
        eat();
        putdown(i);
    }
}

void pickup(int i) {
    wait(mutex);
    state[i] = HUNGRY;
    test(i);
    signal(mutex);
    wait(self[i]);  // Wait until forks available
}

void test(int i) {
    if(state[i]==HUNGRY && state[LEFT]!=EATING && state[RIGHT]!=EATING) {
        state[i] = EATING;
        signal(self[i]);
    }
}
```

**GATE Important Points:**
- Deadlock in dining philosophers
- Solutions to avoid deadlock

---

### DAY 18: Monitors and Other Synchronization Mechanisms

**Theory Learning Goals:**
- Learn about monitors
- Understand message passing
- Learn about condition variables

**Monitors:**
- High-level synchronization construct
- Encapsulates shared data and procedures
- Automatic mutual exclusion
- Condition variables for waiting

**Message Passing:**
- Used for interprocess communication
- Can be synchronous or asynchronous
- Used in distributed systems

**GATE Important Points:**
- Monitor concept
- Condition variables

**Interview FAQ:**
- What is a monitor in OS?
- How does monitor differ from semaphore?

---

### DAY 19: Practice Problems - Process Synchronization

**GATE Problems:**

1. **GATE 2020:** Consider a counting semaphore S. The operation wait(S) and signal(S) are defined as:
   wait(S): while(S <= 0); S = S - 1;
   signal(S): S = S + 1;
   
   Initially, S = 5. Then the number of processes that can execute wait(S) before a signal(S) is executed is?

2. **GATE 2019:** In a producer-consumer problem using semaphores, what is the minimum number of semaphores required?

3. **GATE 2018:** Consider Peterson's algorithm for two processes. Which of the following is TRUE?

**Practical Assignment:**
- Implement readers-writers problem using pthreads
- Use mutex and condition variables

---

### DAY 20: Revision - Process Management and Synchronization

**Weekly Revision Goals:**
- Review all concepts from Days 5-19
- Clear any doubts
- Solve mixed problems

**Self-Test Questions:**
1. Draw and explain the process state diagram
2. Explain fork() and exec() system calls
3. Compare all CPU scheduling algorithms
4. Explain critical section problem
5. Solve a problem on SJF and RR scheduling

**Diagram Practice:**
- Process state diagram
- PCB structure
- CPU scheduling Gantt charts
- Synchronization problem diagrams

---

### DAY 21: Deadlock - Introduction and Characterization

**Theory Learning Goals:**
- Understand what is deadlock
- Learn the necessary conditions for deadlock
- Understand resource allocation graph

**Concepts to Master:**
- Deadlock definition
- Four necessary conditions:
  1. Mutual Exclusion
  2. Hold and Wait
  3. No Preemption
  4. Circular Wait

**Resource Allocation Graph (RAG):**
- Processes (circles)
- Resources (squares)
- Request edge (P → R)
- Assignment edge (R → P)

**Important Diagrams:**
```
With Deadlock (Cycle exists):
P1 → R1 → P2 → R2 → P1

Without Deadlock (Cycle but no deadlock):
P1 → R1 → P2 → R2 → P1 (but R2 has instance available)
```

**GATE Important Points:**
- All four conditions must hold for deadlock
- RAG: if cycle → possible deadlock; if no cycle → no deadlock

---

### DAY 22: Deadlock Prevention and Avoidance

**Theory Learning Goals:**
- Learn methods to prevent deadlock
- Learn Banker's algorithm for avoidance

**Deadlock Prevention:**
- Eliminate Mutual Exclusion: Not always possible
- Eliminate Hold and Wait: Request all resources at once
- Add Preemption: Allow preemption of resources
- Eliminate Circular Wait: Define ordering of resources

**Deadlock Avoidance:**
- Banker's Algorithm
- Safe State: There exists a safe sequence
- Resource Allocation Graph Algorithm (one instance per resource type)

**Banker's Algorithm:**
- Need Matrix: Maximum - Allocation
- Available Vector
- Work and Finish vectors
- Safety Algorithm

**Example:**
```
Processes: P0, P1, P2
Resources: A, B, C (3, 3, 2)

Allocation    Max     Need
P0: 1 0 0    1 1 1   0 1 1
P1: 5 1 0    5 1 0   0 0 0
P2: 2 1 1    2 1 1   0 0 0

Available: 3 1 1
```

**GATE Important Points:**
- Banker's algorithm for deadlock avoidance
- Safety algorithm steps

---

### DAY 23: Deadlock Detection and Recovery

**Theory Learning Goals:**
- Learn deadlock detection algorithms
- Understand recovery from deadlock

**Deadlock Detection:**
- One instance per resource type: Use RAG
- Multiple instances per resource type: Wait-for graph or detection algorithm

**Detection Algorithm:**
```
Work = Available
Finish[i] = (Allocation[i] == 0) ? true : false

Find process i such that:
Finish[i] == false && Need[i] <= Work

If found: Work += Allocation[i], Finish[i] = true
Repeat until no such process

If Finish[i] == false for any i → Deadlock
```

**Recovery from Deadlock:**
- Process Termination: Abort all or one at a time
- Resource Preemption: Take resources from processes

**GATE Important Points:**
- Detection algorithm steps
- When to invoke detection

---

### DAY 24: Practice Problems - Deadlock

**GATE Problems:**

1. **GATE 2020:** System has 3 processes and 2 resource types. What is the minimum number of instances required to ensure deadlock?

2. **GATE 2019:** Consider the following statements about deadlock:
   S1: Hold and Wait condition can be eliminated by requesting all resources initially
   S2: Circular wait can be eliminated by imposing a total ordering of resource types
   Which is TRUE?

3. **GATE 2018:** Using Banker's algorithm, determine if the following state is safe:
   Allocation: P0(0,1,0), P1(1,0,0), P2(1,0,0)
   Max: P0(7,5,3), P1(3,2,2), P2(9,0,2)
   Available: (1,1,1)

**Practical Assignment:**
Implement Banker's algorithm in C

---

### DAY 25: Memory Management - Introduction and Allocation

**Theory Learning Goals:**
- Understand memory management
- Learn contiguous memory allocation
- Understand memory allocation methods

**Concepts to Master:**
- Memory management goals
- Swapping
- Contiguous memory allocation
- Fixed partitions vs Variable partitions

**Memory Allocation Methods:**
- First Fit: Allocate first hole big enough
- Best Fit: Allocate smallest hole big enough
- Worst Fit: Allocate largest hole
- Next Fit: Start searching from where last allocated

**Fragmentation:**
- External Fragmentation: Total memory enough but not contiguous
- Internal Fragmentation: Allocated more than requested
- Solutions: Compaction, Paging, Segmentation

**Formulas:**
- External Fragmentation: n blocks → can have (n-1) external holes
- Internal Fragmentation: Page size - Block size

**GATE Important Points:**
- Difference between internal and external fragmentation
- Which allocation method causes least external fragmentation?

---

### DAY 26: Paging - Basic Concepts

**Theory Learning Goals:**
- Learn paging concept
- Understand page tables
- Learn about TLB (Translation Lookaside Buffer)

**Paging:**
- Non-contiguous memory allocation
- Fixed size pages, frames
- No external fragmentation
- Some internal fragmentation

**Address Translation:**
- Logical Address: Page Number + Offset
- Physical Address: Frame Number + Offset

**Important Formulas:**
- Number of bits for page offset = log2(page size)
- Number of pages = Logical address space / page size
- Page table size = Number of entries × Entry size

**TLB:**
- Hardware cache for page table entries
- Associative memory
- Hit ratio, effective access time

**Example:**
```
Page Size = 4 KB = 4096 bytes = 2^12 bytes
Offset bits = 12
If logical address space = 32 bits
Then page number bits = 32 - 12 = 20
Number of pages = 2^20
Page table entries = 2^20
```

**GATE Important Points:**
- Address translation calculations
- TLB hit ratio calculations

---

### DAY 27: Paging - Page Tables and Multi-level Paging

**Theory Learning Goals:**
- Learn different page table structures
- Understand inverted page tables
- Learn about segmentation

**Page Table Structures:**
- Hierarchical Paging
- Inverted Page Table
- Hashed Page Table

**Multi-level Paging:**
```
Logical Address:
| P1 | P2 | Offset |
  |    |    └── Page offset
  |    └────── Outer page index
  └──────────── Page directory
```

**Inverted Page Table:**
- One entry per frame
- Contains: Process ID, Page Number, Frame Number
- Reduces memory but increases search time

**Segmentation:**
- Variable-sized segments
- Logical view of memory
- Segment table: Base, Limit

**Important Diagram:**
```
Segmentation:
┌─────────────────────────────────────────┐
│  Program                                │
│  ┌─────┐ ┌─────┐ ┌─────┐ ┌─────┐       │
│  │main │ │func1│ │func2│ │array│       │
│  └─────┘ └─────┘ └─────┘ └─────┘       │
│    0      1000    2000    5000         │
└─────────────────────────────────────────┘

Physical Memory:
┌─────┬─────┬─────┬─────┬─────┬─────┐
│     │main │     │func1│func2│array│
└─────┴─────┴─────┴─────┴─────┴─────┘
```

**GATE Important Points:**
- Multi-level page table calculations
- Segmentation vs Paging

---

### DAY 28: Practice Problems - Paging

**GATE Problems:**

1. **GATE 2020:** A system has 16-bit logical address space, page size 4KB. How many entries in page table if single-level? If two-level with 8-bit outer page?

2. **GATE 2019:** Consider a system with TLB hit ratio 80%, TLB access time 20ns, memory access time 100ns. What is effective access time?

3. **GATE 2018:** In a paged memory system, page table is stored in main memory. TLB is used. What is effective access time?

**Solution for Problem 2:**
- TLB Hit (80%): Time = 20 + 100 = 120 ns
- TLB Miss (20%): Time = 20 + 100 + 100 = 220 ns
- Effective = 0.8 × 120 + 0.2 × 220 = 96 + 44 = 140 ns

---

### DAY 29: Virtual Memory - Demand Paging

**Theory Learning Goals:**
- Understand virtual memory concept
- Learn about demand paging
- Understand page fault handling

**Virtual Memory:**
- Allows execution of processes not completely in memory
- Gives illusion of larger memory
- Benefits: More processes, Less I/O, More efficient multiprogramming

**Demand Paging:**
- Pages loaded only when needed
- Valid-Invalid bit for page presence
- Page fault occurs when accessing invalid page

**Page Fault Handling Steps:**
1. Check if reference is valid
2. If invalid → Terminate
3. If valid but not in memory → Bring from disk
4. Find free frame
5. Read page from disk to frame
6. Modify page table
7. Restart instruction

**GATE Important Points:**
- Page fault handling procedure
- Effective access time with page faults

---

### DAY 30: Page Replacement Algorithms

**Theory Learning Goals:**
- Learn different page replacement algorithms
- Understand optimal, FIFO, LRU, and others

**FIFO (First In First Out):**
- Replace oldest page
- Simple but may cause Belady's Anomaly

**Optimal (OPT):**
- Replace page not used for longest time in future
- Minimum page faults
- Not implementable in practice (used for comparison)

**LRU (Least Recently Used):**
- Replace page not used for longest time in past
- Good approximation of OPT
- Stack algorithm (no Belady's anomaly)

**Clock (Second Chance):**
- Use reference bit
- Circular scan
- Approximation of LRU

**Belady's Anomaly:**
- Page faults can increase when increasing frames for FIFO

**Algorithm Comparison Table:**
```
| Algorithm | Belady's Anomaly | Implementation |
|-----------|------------------|----------------|
| FIFO      | Yes              | Easy           |
| OPT       | No               | Impossible     |
| LRU       | No               | Difficult      |
| Clock     | No               | Medium         |
```

**GATE Important Points:**
- All algorithms and their behavior
- Belady's anomaly in FIFO

---

### DAY 31: Practice Problems - Page Replacement

**GATE Problems:**

1. **GATE 2020:** Reference string: 1,2,3,4,1,2,5,1,2,3,4,5. Using LRU with 4 frames, find number of page faults.

2. **GATE 2019:** Reference string: 0,1,2,3,0,1,4,0,1,2,3,4. Using FIFO, 3 frames → 9 faults. With 4 frames → ?

3. **GATE 2018:** Which page replacement algorithm may suffer from Belady's anomaly?

**Practical Assignment:**
Implement FIFO, LRU, and Optimal page replacement in C

---

### DAY 32: Thrashing and Working Set Model

**Theory Learning Goals:**
- Understand thrashing
- Learn working set model
- Understand page fault frequency

**Thrashing:**
- Excessive page faults
- CPU utilization drops
- OS spends time in swapping

**Working Set Model:**
- Set of pages process is actively using
- Working set size = number of pages in working set
- If working set > frames → thrashing

**Page Fault Frequency:**
- Too high → Increase allocation
- Too low → Decrease allocation
- Keep within acceptable range

**GATE Important Points:**
- Thrashing definition and causes
- Working set concept

---

### DAY 33: Revision - Memory Management

**Weekly Revision Goals:**
- Review all concepts from Days 25-32
- Solve mixed problems
- Practice calculations

**Self-Test Questions:**
1. Explain paging and segmentation
2. Difference between external and internal fragmentation
3. Calculate effective access time with TLB
4. Solve page replacement problem
5. Explain thrashing

---

### DAY 34: File Systems - Concepts and Organization

**Theory Learning Goals:**
- Learn about files and file systems
- Understand file attributes
- Learn about directory structure

**File Concept:**
- Logical storage unit
- Named collection of related information
- Attributes: Name, Identifier, Type, Location, Size, Protection, Time/Date

**File Operations:**
- Create, Read, Write, Reposition, Delete, Truncate

**Directory:**
- Files that contain file names and attributes
- Single-level, Two-level, Hierarchical, Acyclic-graph, General graph

**Directory Operations:**
- Search, Create, Delete, List, Rename

**GATE Important Points:**
- Directory structure comparisons
- File attributes

---

### DAY 35: File Allocation Methods

**Theory Learning Goals:**
- Learn contiguous allocation
- Learn linked allocation
- Learn indexed allocation

**Contiguous Allocation:**
- Each file gets consecutive blocks
- Simple, Direct access
- Problem: External fragmentation, Finding space for file

**Linked Allocation:**
- Blocks scattered, pointer in each block
- No external fragmentation
- Problem: No random access, Pointer overhead

**Indexed Allocation:**
- Separate index block contains pointers
- No external fragmentation
- Direct access possible
- Problem: Index block overhead

**Combined Approach (Unix Inode):**
- 12 direct pointers
- 1 indirect, 1 double indirect, 1 triple indirect

**GATE Important Points:**
- Comparisons of allocation methods
- Calculations for each method

---

### DAY 36: Free Space Management and Disk Structure

**Theory Learning Goals:**
- Learn free space management
- Understand disk organization
- Learn about disk scheduling

**Free Space Management:**
- Bit Vector/Bit Map
- Linked List
- Grouping
- Counting

**Disk Structure:**
- Disk is divided into tracks
- Tracks divided into sectors
- Cylinders: Same track on all surfaces

**Disk Scheduling:**
- Seek time: Head movement
- Rotational latency: Wait for sector
- Transfer time

**GATE Important Points:**
- Free space management methods
- Disk access time calculations

---

### DAY 37: Disk Scheduling Algorithms

**Theory Learning Goals:**
- Learn various disk scheduling algorithms
- Understand FCFS, SSTF, SCAN, C-SCAN, LOOK

**FCFS:**
- Service in order of arrival
- Simple but not optimal

**SSTF (Shortest Seek Time First):**
- Select closest request
- May cause starvation

**SCAN (Elevator):**
- Head moves in one direction, services all requests
- Then reverses direction
- Also called elevator algorithm

**C-SCAN:**
- Circular scan
- Returns to beginning without servicing
- Provides uniform wait time

**LOOK:**
- Like SCAN but doesn't go to end

**Example:**
```
Request queue: 98, 183, 37, 122, 14, 124, 65, 67
Head starts at 53

FCFS: 53→98→183→37→122→14→124→65→67 → Total seek = 645

SSTF: 53→65→67→37→14→98→122→124→183 → Total seek = ?

SCAN: 53→37→14→0→65→67→98→122→124→183 → Total seek = ?

C-SCAN: 53→65→67→98→122→124→183→199→0→14→37 → Total seek = ?
```

**GATE Important Points:**
- All algorithms and their behavior
- Compare seek times

---

### DAY 38: Practice Problems - File Systems and Disk Scheduling

**GATE Problems:**

1. **GATE 2020:** Disk request queue: 98, 183, 37, 122, 14, 124, 65, 67. Head at 53. Using SSTF, calculate total seek time.

2. **GATE 2019:** Which file allocation method allows efficient random access?

3. **GATE 2018:** In linked allocation, if each block is 512 bytes and each block has 4-byte pointer, how much space is wasted?

**Practical Assignment:**
Implement FCFS, SSTF, SCAN disk scheduling in C

---

### DAY 39: I/O Systems - Concepts

**Theory Learning Goals:**
- Learn about I/O devices
- Understand I/O organization
- Learn about device controllers

**I/O Devices:**
- Block devices: Disk, Tape (random access)
- Character devices: Terminal, Printer (stream access)
- Network devices

**Device Controller:**
- Interface between device and CPU
- Contains: Data registers, Status registers, Control registers
- Uses: Polling, Interrupts, DMA

**I/O Techniques:**
- Programmed I/O: CPU busy-waits
- Interrupt-driven I/O: Device interrupts CPU
- DMA (Direct Memory Access): DMA controller transfers data

**DMA:**
- CPU initializes transfer
- DMA handles data movement
- CPU can do other work
- Reduces CPU overhead

**GATE Important Points:**
- DMA advantages
- Polling vs Interrupt vs DMA

---

### DAY 40: Protection and Security - Introduction

**Theory Learning Goals:**
- Understand protection
- Learn about access control
- Understand security policies

**Protection:**
- Mechanism for controlling access to resources
- Goals: Prevent unauthorized access, Ensure proper usage
- Domain of protection: User, Process

**Access Control:**
- Access Matrix
  - Rows: Domains
  - Columns: Objects
  - Entries: Rights (read, write, execute)

**Implementation of Access Matrix:**
- Global table: List of (domain, object, rights)
- Access control lists (ACL): Per object
- Capability lists: Per domain

**Security:**
- Threats: Intrusion, Viruses, Worms
- Protection mechanisms: Authentication, Encryption

**GATE Important Points:**
- Access matrix concept
- ACL vs Capability lists

---

### DAY 41: Linux Internals - Introduction

**Theory Learning Goals:**
- Learn about Linux kernel
- Understand Linux architecture
- Learn about process management in Linux

**Linux Architecture:**
- User Space: Applications, glibc
- Kernel Space: System calls, Kernel
- Hardware

**Linux Kernel:**
- Monolithic but modular
- Supports loadable modules

**Linux Process Management:**
- PID (Process ID)
- Process states: Running, Interruptible, Uninterruptible, Zombie, Stopped
- fork(), vfork(), clone()
- Process scheduling: CFS

**Linux Memory Management:**
- Virtual memory
- Page tables
- Swapping
- Buddy system, Slab allocator

**GATE Important Points:**
- Linux kernel architecture
- Process states in Linux

---

### DAY 42: Linux Commands and System Administration

**Theory Learning Goals:**
- Learn essential Linux commands
- Understand process control in Linux
- Learn about monitoring

**Process Management Commands:**
- ps: Process status
- top: System monitor
- kill: Send signals
- nice: Set priority
- renice: Change priority

**Memory Commands:**
- free: Memory info
- vmstat: Virtual memory stats
- cat /proc/meminfo

**Disk Commands:**
- df: Disk space
- du: Directory usage

**System Monitoring:**
- uptime: System load
- w: Who is logged in
- who: Current users

**GATE Important Points:**
- Basic Linux commands for OS understanding
- Process management in Linux

**Practical Assignment:**
Master all Linux commands covered today

---

### DAY 43: Shell Scripting - Basics

**Theory Learning Goals:**
- Learn bash scripting basics
- Understand variables and control structures
- Learn to write automation scripts

**Variables:**
```
bash
# Defining variables
name="John"
age=25

# Using variables
echo "Name: $name"
echo "Age: $age"
```

**Control Structures:**
```bash
# If-else
if [ $age -gt 18 ]; then
    echo "Adult"
else
    echo "Minor"
fi

# For loop
for i in {1..5}; do
    echo "Number: $i"
done

# While loop
count=1
while [ $count -le 5 ]; do
    echo $count
    count=$((count+1))
done
```

**Functions:**
```
bash
greet() {
    echo "Hello, $1!"
}
greet "World"
```

**GATE Important Points:**
- Basic shell scripting constructs
- Not typically asked in GATE but important for practical skills

---

### DAY 44: Advanced Shell Scripting

**Theory Learning Goals:**
- Learn advanced scripting
- Create scripts for OS monitoring

**Script for Process Monitoring:**
```
bash
#!/bin/bash
# Monitor top CPU processes

echo "Top 5 CPU consuming processes:"
ps aux --sort=-%cpu | head -6

echo ""
echo "Top 5 Memory consuming processes:"
ps aux --sort=-%mem | head -6
```

**Script for Disk Usage:**
```
bash
#!/bin/bash
# Check disk usage

df -h | grep -v tmpfs

echo ""
echo "Directories using most space:"
du -h --max-depth=1 | sort -hr | head -10
```

**Practical Assignment:**
Create a script to monitor system resources and log to file

---

### DAY 45: Revision - File Systems, I/O, Protection

**Weekly Revision Goals:**
- Review all concepts from Days 34-44
- Solve mixed problems

**Self-Test Questions:**
1. Compare file allocation methods
2. Explain disk scheduling algorithms
3. Difference between polling and interrupts
4. Explain access matrix

---

### DAY 46: Interview Questions - Process Management

**Most Important Interview Questions:**

1. **What is a process? How is it different from a program?**
   - Process is a program in execution
   - Program is passive, process is active
   - Process has: code, data, stack, PCB

2. **Explain process state diagram.**
   - New → Ready → Running → Terminated
   - Running → Waiting → Ready
   - Ready → Running (scheduler dispatch)

3. **What is PCB? What does it contain?**
   - Process Control Block
   - Contains: PID, state, PC, registers, memory info, I/O info, accounting

4. **What is a thread? Benefits of multithreading?**
   - Lightweight process
   - Shares resources within process
   - Benefits: Responsiveness, Resource sharing, Economy, Scalability

5. **Difference between user thread and kernel thread?**
   - User thread: Managed by thread library
   - Kernel thread: Managed by OS
   - User threads need mapping to kernel threads

---

### DAY 47: Interview Questions - CPU Scheduling

**Important Interview Questions:**

1. **What is CPU scheduling? Why is it needed?**
   - Process of selecting which process to run on CPU
   - Needed for multiprogramming, better utilization

2. **What is the difference between preemptive and non-preemptive scheduling?**
   - Preemptive: Process can be preempted by OS
   - Non-preemptive: Process runs to completion or waits voluntarily

3. **What is turnaround time? How to calculate?**
   - Time from process submission to completion
   - Turnaround = Completion time - Arrival time

4. **What is waiting time? How to calculate?**
   - Time process spends in ready queue
   - Waiting = Turnaround time - Burst time

5. **Which scheduling algorithm gives minimum average waiting time?**
   - SJF (Shortest Job First) - for non-preemptive
   - SRTF (Shortest Remaining Time First) - for preemptive

6. **What is convoy effect in FCFS?**
   - Short processes wait for long CPU-bound process
   - Leads to poor CPU utilization

7. **What is starvation? Which algorithms suffer from it?**
   - Indefinite waiting
   - SJF, Priority scheduling can cause starvation
   - Aging can solve starvation

---

### DAY 48: Interview Questions - Process Synchronization

**Important Interview Questions:**

1. **What is a race condition?**
   - When multiple processes access and modify shared data
   - Final result depends on execution order

2. **What is critical section? Requirements for its solution?**
   - Code that accesses shared resources
   - Requirements: Mutual exclusion, Progress, Bounded waiting

3. **What is a semaphore? Types?**
   - Integer variable with two atomic operations: wait() and signal()
   - Types: Binary (mutex), Counting

4. **Difference between semaphore and mutex?**
   - Semaphore: Signaling mechanism, can have multiple slots
   - Mutex: Locking mechanism, only one can acquire

5. **What is a monitor?**
   - High-level synchronization construct
   - Encapsulates shared data and procedures
   - Automatic mutual exclusion

6. **Explain producer-consumer problem.**
   - Producer produces, Consumer consumes
   - Buffer has finite capacity
   - Need to prevent overflow and underflow

7. **Explain dining philosophers problem.**
   - 5 philosophers, 5 forks
   - Need 2 forks to eat
   - Classic deadlock problem

---

### DAY 49: Interview Questions - Deadlocks

**Important Interview Questions:**

1. **What is a deadlock? Four necessary conditions?**
   - Circular wait for resources held by others
   - Conditions: Mutual exclusion, Hold and wait, No preemption, Circular wait

2. **Difference between deadlock prevention and avoidance?**
   - Prevention: Eliminate one of four conditions
   - Avoidance: Safe state, Banker's algorithm

3. **What is Banker's algorithm?**
   - Deadlock avoidance algorithm
   - Checks if allocation leads to safe state
   - Uses Need matrix = Max - Allocation

4. **What is a safe state?**
   - There exists a sequence where all processes can complete
   - No deadlock in safe state

5. **What is resource allocation graph?**
   - Graph showing processes and resources
   - Request edge, Assignment edge
   - Cycle → possible deadlock

6. **How to recover from deadlock?**
   - Process termination
   - Resource preemption

---

### DAY 50: Interview Questions - Memory Management

**Important Interview Questions:**

1. **What is paging? Advantages and disadvantages?**
   - Non-contiguous allocation using fixed-size pages
   - Advantages: No external fragmentation
   - Disadvantages: Internal fragmentation, Page table overhead

2. **What is segmentation?**
   - Variable-sized logical divisions
   - Each segment has: Base, Limit

3. **What is a page table? Types?**
   - Maps virtual addresses to physical
   - Types: Single-level, Multi-level, Inverted

4. **What is TLB? How does it improve performance?**
   - Translation Lookaside Buffer
   - Cache for page table entries
   - Reduces memory access time

5. **What is virtual memory? Benefits?**
   - Allows execution of processes not completely in memory
   - Benefits: Larger address space, More processes

6. **What is page fault? How is it handled?**
   - Accessing page not in memory
   - Steps: Check validity, Find free frame, Load page, Update table, Restart

7. **What is thrashing?**
   - Excessive paging
   - CPU utilization drops
   - Caused by too many processes or too few frames

8. **Explain Belady's anomaly.**
   - Page faults increase when increasing frames
   - Happens in FIFO, not in stack algorithms (LRU)

---

### DAY 51: Interview Questions - File Systems and Disk Scheduling

**Important Interview Questions:**

1. **What are the different file allocation methods?**
   - Contiguous: Sequential, direct access, external fragmentation
   - Linked: No fragmentation, no random access
   - Indexed: Random access, index block overhead

2. **What is an inode?**
   - Index node in Unix
   - Contains: File attributes, Data block pointers

3. **Explain disk scheduling algorithms.**
   - FCFS: First come first served
   - SSTF: Shortest seek time first
   - SCAN: Elevator algorithm
   - C-SCAN: Circular scan

4. **What is seek time? Rotational latency?**
   - Seek time: Time for head to move to track
   - Rotational latency: Time to rotate to correct sector

5. **Difference between internal and external fragmentation?**
   - Internal: Allocated more than needed
   - External: Available memory not contiguous

---

### DAY 52: GATE Practice - Process Management

**GATE Problems:**

1. **GATE 2021:** Consider a process with 3 threads. The process has resources A (3 instances), B (2 instances). Thread 1 holds 1 A, Thread 2 holds 1 B, Thread 3 holds nothing. Maximum requirement: Thread 1 (2 A), Thread 2 (1 A, 1 B), Thread 3 (2 B). Is system in safe state?

2. **GATE 2020:** What is the minimum number of semaphores for producer-consumer with n buffers?

3. **GATE 2019:** Round Robin with time quantum = 2. Processes: P1(3), P2(2), P3(1). Calculate average waiting time.

4. **GATE 2018:** SJF with arrival times. Which has minimum average waiting?

---

### DAY 53: GATE Practice - Synchronization and Deadlock

**GATE Problems:**

1. **GATE 2021:** Which of the following is NOT a condition for deadlock?
   a) Mutual Exclusion b) Hold and Wait c) No Preemption d) Starvation

2. **GATE 2020:** In Banker's algorithm, if the need matrix is less than or equal to work for all processes, then the system is in?

3. **GATE 2019:** Peterson's algorithm for 2 processes uses which variables?

4. **GATE 2018:** A system has 3 processes and 3 resource types. The maximum demands: P1(3,4,3), P2(1,2,3), P2(3,0,5). Available (1,2,1). Is safe?

---

### DAY 54: GATE Practice - Memory Management

**GATE Problems:**

1. **GATE 2021:** Page size = 4KB, logical address = 32 bits. How many bits for page number?

2. **GATE 2020:** TLB has 80% hit rate, 20ns access, 100ns memory. Effective access time?

3. **GATE 2019:** LRU with 3 frames. Reference string: 1,2,3,4,1,2,5,1,2,3,4,5. How many page faults?

4. **GATE 2018:** External fragmentation occurs in which allocation?

---

### DAY 55: GATE Practice - File Systems and Disk Scheduling

**GATE Problems:**

1. **GATE 2021:** Disk rotates at 7200 RPM. Average rotational latency?

2. **GATE 2020:** SCAN algorithm with head at 50, requests at 10, 22, 37, 62, 85, 90, 100, 115, 120. Calculate seek time.

3. **GATE 2019:** Which file allocation method supports direct access?

4. **GATE 2018:** In indexed allocation, if block size = 4KB and address = 4 bytes, how many entries?

---

### DAY 56: Mini Project 1 - Process Scheduler Simulator

**Project Description:**
Create a CPU scheduling simulator in C that demonstrates:
- FCFS, SJF, Priority, Round Robin scheduling
- Calculate and display metrics
- Interactive UI

**Features:**
1. Accept process details (arrival time, burst time, priority)
2. Implement all four scheduling algorithms
3. Generate Gantt chart
4. Calculate and display: Turnaround time, Waiting time, Average times
5. User can choose algorithm

**Implementation Approach:**
```
c
struct Process {
    int pid;
    int arrival_time;
    int burst_time;
    int priority;
    int completion_time;
    int turnaround_time;
    int waiting_time;
    int remaining_time;
};
```

**Expected Output:**
- Gantt chart visualization
- Table with all metrics
- Average turnaround time, waiting time

---

### DAY 57: Mini Project 2 - Banker's Algorithm Implementation

**Project Description:**
Implement Banker's algorithm for deadlock avoidance

**Features:**
1. Accept number of processes and resources
2. Input maximum demand, allocation, available
3. Check if system is in safe state
4. Determine safe sequence
5. Check if request can be granted

**Algorithm Steps:**
1. Calculate Need matrix (Need = Max - Allocation)
2. Find process with Need <= Available
3. Add its Allocation to Available
4. Repeat until all processes complete or no such process exists

---

### DAY 58: Mini Project 3 - Page Replacement Simulator

**Project Description:**
Implement page replacement algorithms simulator in C

**Features:**
1. Implement FIFO, LRU, and Optimal algorithms
2. Accept reference string and frame count
3. Display page fault count for each algorithm
4. Visual step-by-step display

**Implementation Example:**
```
c
// LRU Page Replacement
void lru_page_replacement(int reference_string[], int n, int frames) {
    int frame_array[frames];
    int page_faults = 0;
    int counter[frames]; // Track last use time
    
    for(int i = 0; i < frames; i++) {
        frame_array[i] = -1;
        counter[i] = 0;
    }
    
    for(int i = 0; i < n; i++) {
        int page = reference_string[i];
        int found = 0;
        
        // Check if page is already in frame
        for(int j = 0; j < frames; j++) {
            if(frame_array[j] == page) {
                found = 1;
                counter[j] = i; // Update last use time
                break;
            }
        }
        
        // Page fault - replace LRU page
        if(!found) {
            // Find LRU page
            int lru = 0;
            for(int j = 1; j < frames; j++) {
                if(counter[j] < counter[lru])
                    lru = j;
            }
            frame_array[lru] = page;
            counter[lru] = i;
            page_faults++;
        }
    }
    printf("LRU Page Faults: %d\n", page_faults);
}
```

---

### DAY 59: Mini Project 4 - Producer-Consumer Problem

**Project Description:**
Implement producer-consumer using semaphores and pthreads

**Features:**
1. Bounded buffer implementation
2. Multiple producers and consumers
3. Semaphore-based synchronization
4. Thread-safe operations

---

### DAY 60: Mini Project 5 - Dining Philosophers

**Project Description:**
Implement dining philosophers problem

**Features:**
1. Thread-based implementation
2. Multiple solutions
3. Deadlock demonstration
4. Solution comparison

---

### DAY 61-67: Protection and Security - Advanced Topics

**Advanced Security Concepts:**

**Authentication Methods:**
- Password-based
- Biometric
- Token-based
- Multi-factor authentication

**Security Threats:**
- Viruses: Self-replicating, attach to programs
- Worms: Self-replicate, spread through networks
- Trojan horses: Disguised as legitimate software
- Spyware: Monitor user activity
- Phishing: Deceptive information gathering

**Encryption:**
- Symmetric (DES, AES)
- Asymmetric (RSA)
- Hash functions (MD5, SHA)

**Linux Security:**
- File permissions: rwx for owner, group, others
- User management: /etc/passwd, /etc/shadow
- sudo access
- SELinux, AppArmor

---

### DAY 68-74: Linux Kernel Deep Dive

**Linux Kernel Architecture:**

**System Call Interface:**
- Transition from user space to kernel space
- Common system calls: read, write, fork, exec, open, close

**Process Scheduling in Linux:**
- O(1) scheduler (older)
- CFS (Completely Fair Scheduler)
- Real-time scheduling: SCHED_FIFO, SCHED_RR, SCHED_DEADLINE

**Linux Memory Management:**
- Page allocator: Buddy system
- Slab allocator: kmalloc, kmem_cache
- Virtual memory: vmalloc, mmap

**File System in Linux:**
- VFS (Virtual File System)
- ext4, xfs, btrfs
- /proc and /sys filesystems

---

### DAY 75-81: Advanced Shell Scripting and Automation

**Advanced Scripting Concepts:**

**String Operations:**
```
bash
# String length
str="Hello World"
echo ${#str}  # 11

# Substring
echo ${str:0:5}  # Hello

# Pattern matching
echo ${str//World/Universe}
```

**Arrays:**
```
bash
arr=(1 2 3 4 5)
echo ${arr[0]}
echo ${arr[@]}  # All elements
```

**Process Management Script:**
```
bash
#!/bin/bash
# Auto-kill high CPU process

threshold=80
while true; do
    ps aux --sort=-%cpu | tail -n +2 | while read user pid cpu mem cmd; do
        if (( $(echo "$cpu > $threshold" | bc -l) )); then
            echo "High CPU: $pid ($cpu%) - $cmd"
            # kill -9 $pid
        fi
    done
    sleep 60
done
```

---

### DAY 82-85: Comprehensive GATE Revision

**Important GATE Topics to Revise:**

**Process Management (15-20 marks):**
- Process state diagram
- PCB structure
- CPU scheduling algorithms with calculations
- Thread vs process

**Synchronization (12-15 marks):**
- Critical section problem
- Semaphores and mutex
- Classical problems (producer-consumer, readers-writers, dining philosophers)
- Deadlock conditions

**Memory Management (15-20 marks):**
- Paging and segmentation
- Page table structures
- Virtual memory concepts
- Page replacement algorithms with calculations

**Deadlock (8-10 marks):**
- Banker's algorithm
- Safe state
- Resource allocation graph

**File Systems and Disk Scheduling (10-12 marks):**
- File allocation methods
- Disk scheduling algorithms
- Free space management

---

### DAY 86-88: Mock Tests and Practice

**Test Strategy:**
- Solve 2-3 full-length mock tests
- Analyze weak areas
- Focus on time management

**Important Formulas Summary:**
```
Turnaround Time = Completion Time - Arrival Time
Waiting Time = Turnaround Time - Burst Time
Effective Access Time = (Hit Ratio × (TLB + Memory)) + (Miss Ratio × (TLB + 2 × Memory))
Page Fault Rate = Page Faults / Total References
Seek Time = |Current Track - Target Track|
Turnaround Time (Disk) = Seek Time + Rotational Latency + Transfer Time
```

---

### DAY 89-90: Final Preparation and Project Completion

**Final Day Checklist:**
- [ ] Revise all important diagrams
- [ ] Review all formulas
- [ ] Go through interview questions
- [ ] Complete final project
- [ ] Get adequate rest

---

## 10 Most Important OS Diagrams to Master

### 1. Process State Diagram
```
         ┌──────────┐
         │   New    │
         └────┬─────┘
              │ Admit
              ▼
         ┌──────────┐     Dispatch      ┌──────────┐
         │  Ready   │◄────────────────►│ Running  │
         └────┬─────┘                   └────┬─────┘
              │                                │
              │ Timeout                        │ I/O or Event Wait
              │                                │
              ▼                                ▼
         ┌──────────┐                   ┌──────────┐
         │ Waiting  │───I/O Complete───►│  Ready   │
         └──────────┘                   └──────────┘
              │
              │ Exit
              ▼
         ┌──────────┐
         │ Terminated│
         └──────────┘
```

### 2. PCB (Process Control Block) Structure
```
┌────────────────────────────────────────────┐
│         PROCESS CONTROL BLOCK              │
├────────────────────────────────────────────┤
│ Process ID (PID)                          │
│ Process State (New/Ready/Running/Waiting) │
│ Program Counter (PC)                      │
│ CPU Registers                              │
│ Memory Limits (Base, Limit)               │
│ List of Open Files                        │
│ CPU Scheduling Information                │
│ Memory Management Information             │
│ I/O Status Information                    │
│ Accounting Information                    │
│ Pointer to Parent Process                │
│ Pointer to Child Processes                │
└────────────────────────────────────────────┘
```

### 3. CPU Scheduling Gantt Charts (FCFS, SJF, RR)
```
FCFS:   | P1(0-10) | P2(10-15) | P3(15-23) |
        0         10         15          23

SJF:    | P4(0-3)  | P1(3-9)  | P3(9-16) | P2(16-24) |
        0         3          9          16           24

RR(q=2):|P1|P2|P3|P1|P3|P2|P3|P1|P3|
        0 2 4 6 8 10 12 14 16 18
```

### 4. Multi-level Feedback Queue
```
┌─────────────────────────────────────────────────────┐
│              Multi-level Feedback Queue              │
│  ┌──────────┐    ┌──────────┐    ┌──────────┐     │
│  │  Queue 0 │───►│  Queue 1 │───►│  Queue 2 │────►│
│  │   RR     │    │   RR     │    │   FCFS   │     │
│  │  q = 2   │    │  q = 4   │    │          │     │
│  │ Highest  │    │          │    │  Lowest  │     │
│  └──────────┘    └──────────┘    └──────────┘     │
└─────────────────────────────────────────────────────┘
```

### 5. Resource Allocation Graph

**With Deadlock:**
```
    R1          R2
   ┌───┐       ┌───┐
   │ 1 │       │ 1 │
   └───┘       └───┘
    ▲ ▲         ▲ ▲
    │ │         │ │
P1──┘ └───┐   P2──┘ └───┐
  request  │   request  │
            P1──────────P2
         (circular wait)
```

**Without Deadlock:**
```
    R1          R2
   ┌───┐       ┌───┐
   │ 2 │       │ 1 │
   └───┘       └───┘
    ▲ ▲         ▲
    │ │         │
P1──┘ └───┐   P2──┘
  request  │   request
            P1───────►P2
         (no circular wait due to available R2)
```

### 6. Paging Address Translation
```
Logical Address (32 bits):
┌────────────────────┬───────────────────┐
│   Page Number      │    Offset         │
│      (20 bits)     │    (12 bits)      │
└────────────────────┴───────────────────┘

Physical Address:
┌────────────────────┬───────────────────┐
│   Frame Number     │    Offset         │
│      (20 bits)     │    (12 bits)      │
└────────────────────┴───────────────────┘

Page Table Entry:
┌─────────────┬──────┬──────┬──────┬──────┐
│  Frame No  │Valid │ Dirty│ Ref  │ Acc  │
└─────────────┴──────┴──────┴──────┴──────┘
```

### 7. Segmentation
```
Logical Address:
┌──────────────┬────────────┐
│ Segment No   │  Offset    │
└──────────────┴────────────┘

Segment Table:
┌────────────┬────────┬────────────┐
│ Seg No     │  Base  │   Limit    │
├────────────┼────────┼────────────┤
│     0      │  1000  │    500     │
│     1      │  2500  │    800     │
│     2      │  5000  │    400     │
└────────────┴────────┴────────────┘

Physical Memory:
┌────────┬────────┬────────┬────────┬────────┐
│ Seg 0  │        │ Seg 1  │        │ Seg 2  │
│1000-1500       │2500-3300        │5000-5400
└────────┴────────┴────────┴────────┴────────┘
```

### 8. Disk Scheduling Algorithms
```
FCFS: 53→98→183→37→122→14→124→65→67
      |__|__|__|__|__|__|__|__| total seek

SSTF: 53→65→67→37→14→98→122→124→183
      |__|__|__|__|__|__|__|__|__|

SCAN: 53→37→14→0→65→67→98→122→124→183→199
      |__|__|__|__|__|__|__|__|__|___|

C-SCAN: 53→65→67→98→122→124→183→199→0→14→37
        |__|__|__|__|__|__|__|____|__|__|
```

### 9. Memory Layout
```
┌────────────────────────┐ High Address
│        Stack           │ ← grows down
├────────────────────────┤
│           │            │
│           ▼            │
│     (free memory)      │
│           ▲            │
│           │            │
├────────────────────────┤
│         Heap           │ ← grows up
├────────────────────────┤
│    Uninitialized Data  │
│        (BSS)           │
├────────────────────────┤
│   Initialized Data    │
├────────────────────────┤
│    Text (Code)        │
└────────────────────────┘ Low Address
```

### 10. Page Replacement Flowchart
```
┌─────────────────┐
│  Page Request   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Page in Memory? │
└────────┬────────┘
    Yes/    \No
    │        │
    ▼        ▼
┌────────┐ ┌─────────────────┐
│ Return │ │ Find Empty     │
│  OK    │ │ Frame?         │
└────────┘ └────────┬────────┘
                    │    \Yes
                    │     │
                    ▼     ▼
              ┌─────────┐ ┌─────────┐
              │ Load to │ │ Replace │
              │  Frame  │ │  Victim │
              └────┬────┘ └────┬────┘
                   │          │
                   └────┬─────┘
                        │
                        ▼
                 ┌────────────┐
                 │ Update Page│
                 │    Table   │
                 └─────┬──────┘
                       │
                       ▼
                 ┌────────────┐
                 │  Restart   │
                 │ Instruction│
                 └────────────┘
```

---

## 25 Most Important OS Interview Questions

### Process Management (5 Questions)

**Q1: What is the difference between a process and a program?**
- A program is a passive set of instructions stored on disk
- A process is an active program in execution
- Process has: program code, data, stack, heap, PCB
- Multiple processes can run the same program

**Q2: Explain the process state diagram.**
- New: Process being created
- Ready: Waiting in ready queue for CPU
- Running: Currently executing on CPU
- Waiting: Waiting for I/O or event
- Terminated: Completed execution
- Transitions: New→Ready, Ready→Running (dispatch), Running→Ready (preempt), Running→Waiting, Waiting→Ready

**Q3: What is a zombie process? How to prevent it?**
- Zombie: Process that has terminated but PCB still in memory (parent hasn't read exit status)
- Prevention: Parent must call wait()/waitpid() to read child's exit status
- Or use signal(SIGCHLD, SIG_IGN) to automatically reap children

**Q4: What is fork() system call?**
- Creates a new process (child)
- Returns twice: Parent gets child's PID, child gets 0
- Child gets copy of parent's address space
- Uses Copy-on-Write for efficiency

**Q5: What are the benefits of multithreading?**
- Responsiveness: UI remains responsive
- Resource sharing: Threads share process resources
- Economy: Creating threads is cheaper than processes
- Scalability: Better utilization on multi-core systems

### CPU Scheduling (5 Questions)

**Q6: What is the difference between preemptive and non-preemptive scheduling?**
- Preemptive: OS can forcibly remove CPU from process (time slicing, priority)
- Non-preemptive: Process runs until it blocks or yields CPU
- Preemptive provides better responsiveness but can cause race conditions

**Q7: Which CPU scheduling algorithm gives minimum average waiting time?**
- SJF (Shortest Job First) for non-preemptive
- SRTF (Shortest Remaining Time First) for preemptive
- Problem: Starvation for long processes

**Q8: What is convoy effect in FCFS?**
- Short processes wait behind long CPU-bound process
- Poor CPU and device utilization
- Solution: Use SJF or RR

**Q9: What is starvation? How to solve it?**
- Starvation: Process never gets CPU because others always have priority
- Solutions: Aging (increase priority over time), Fair scheduling

**Q10: What is the effect of time quantum on Round Robin scheduling?**
- Large quantum: Behaves like FCFS, poor response time
- Small quantum: Good response time, high context switch overhead
- Optimal: Should be slightly larger than burst time of typical process

### Process Synchronization (5 Questions)

**Q11: What is a race condition?**
- When multiple processes/threads access and modify shared data concurrently
- Final result depends on execution order
- Must be prevented with synchronization

**Q12: What are the requirements for critical section solution?**
- Mutual Exclusion: Only one thread in critical section
- Progress: If no one in CS and some want to enter, decide quickly
- Bounded Waiting: Limit on number of times others can enter after request

**Q13: Difference between semaphore and mutex?**
- Mutex: Binary semaphore (0 or 1), used for mutual exclusion only
- Counting Semaphore: Can have values 0 to N, used for resource counting
- Both provide blocking/wakeup mechanism
- Mutex has ownership (only owner can release), semaphore doesn't

**Q14: Explain producer-consumer problem.**
- Producer produces items into bounded buffer
- Consumer consumes from buffer
- Must prevent overflow and underflow
- Solution uses: mutex (mutual exclusion), empty (count empty slots), full (count filled slots)

**Q15: Explain dining philosophers problem.**
- 5 philosophers, 5 forks (one between each)
- Need 2 forks to eat
- Classic deadlock demonstration
- Solutions: Resource hierarchy, Arbitrator, State-based (solution shown earlier)

### Deadlock (5 Questions)

**Q16: What are the four necessary conditions for deadlock?**
1. Mutual Exclusion: Resource can't be shared
2. Hold and Wait: Process holds resources while waiting for more
3. No Preemption: Can't forcibly take resources
4. Circular Wait: P1 waits for P2, P2 waits for P3, ..., Pn waits for P1

**Q17: Difference between deadlock prevention and avoidance?**
- Prevention: Eliminate one of the four conditions at design time
- Avoidance: Dynamically analyze resource allocation (Banker's algorithm)
- Prevention is more restrictive, avoidance allows more resource sharing

**Q18: What is Banker's algorithm?**
- Deadlock avoidance algorithm
- Checks if granting request leads to safe state
- Uses Need matrix = Max - Allocation
- Safe state: There exists a sequence where all processes can complete

**Q19: What is a safe state?**
- State where there exists a sequence (safe sequence) of process execution
- All processes can complete without deadlock
- Even if system is in safe state, deadlock can occur if processes behave badly

**Q20: How can we recover from deadlock?**
- Process Termination: Abort one or more processes
- Resource Preemption: Take resources from processes (rollback to previous state)

### Memory Management (5 Questions)

**Q21: What is paging? Advantages and disadvantages?**
- Paging: Divide process into fixed-size pages, physical memory into frames
- Advantages: No external fragmentation, Simple memory allocation
- Disadvantages: Internal fragmentation, Page table overhead, Complex address translation

**Q22: What is segmentation?**
- Variable-sized logical divisions of program
- Each segment has: base address and limit
- Provides logical view of memory
- Combined with paging for benefits of both

**Q23: What is virtual memory? Benefits?**
- Allows execution of processes not completely in memory
- Benefits: Larger address space than physical memory, More processes in memory, Easier programming

**Q24: What is page fault? How is it handled?**
- Page fault: Accessing page not in physical memory
- Steps:
  1. OS checks if reference is valid
  2. If valid, find empty frame
  3. Read page from disk to frame
  4. Update page table
  5. Restart instruction

**Q25: What is thrashing?**
- Excessive page faulting causing poor CPU utilization
- Process spends more time paging than executing
- Caused by too many processes or too few frames
- Solution: Working set model, Page fault frequency control

---

## 20 Most Important GATE OS Topics

### High Weightage Topics (Priority 1)

**1. CPU Scheduling Algorithms (8-10 marks)**
- FCFS, SJF (preemptive/non-preemptive), Priority, Round Robin
- Calculations: Turnaround time, Waiting time, Average times
- Gantt chart drawing
- Algorithm comparisons and characteristics

**2. Process Synchronization (8-10 marks)**
- Critical section problem
- Semaphores (wait, signal)
- Producer-Consumer, Readers-Writers, Dining Philosophers
- Deadlock vs Starvation

**3. Deadlock (6-8 marks)**
- Four necessary conditions
- Banker's algorithm (safety check, resource request)
- Resource Allocation Graph
- Prevention vs Avoidance vs Detection

**4. Memory Management - Paging (8-10 marks)**
- Address translation (logical to physical)
- Page table structures (single-level, multi-level)
- TLB (hit ratio, effective access time)
- Page replacement algorithms

**5. Virtual Memory (6-8 marks)**
- Demand paging
- Page replacement (FIFO, LRU, Optimal)
- Belady's anomaly
- Thrashing, Working set model

### Medium Weightage Topics (Priority 2)

**6. Process Management (5-7 marks)**
- Process vs Program
- PCB, Process states
- fork(), exec(), wait()
- Threads vs Processes

**7. Disk Scheduling (4-6 marks)**
- FCFS, SSTF, SCAN, C-SCAN, LOOK
- Seek time calculations
- Algorithm comparisons

**8. File Systems (4-6 marks)**
- File allocation methods (Contiguous, Linked, Indexed)
- Directory implementations
- Free space management (Bit vector, Linked list)

**9. Page Replacement Algorithms (5-7 marks)**
- FIFO, LRU, Optimal
- Page fault calculations
- Belady's anomaly demonstration

**10. Synchronization Mechanisms (4-5 marks)**
- Mutex vs Semaphore
- Monitors
- Hardware solutions (Test and Set, Swap)

### Lower Weightage Topics (Priority 3)

**11. OS Services and System Calls (2-3 marks)**
- User vs Kernel mode
- System call types
- Bootstrap process

**12. OS Structures (2-3 marks)**
- Monolithic, Layered, Microkernel
- Linux kernel architecture

**13. I/O Systems (2-3 marks)**
- DMA vs Interrupt-driven
- Polling vs Interrupts
- Device controllers

**14. Protection and Security (2-3 marks)**
- Access Matrix
- Authentication methods
- Security threats

**15. Memory Management - Allocation (2-3 marks)**
- First Fit, Best Fit, Worst Fit
- Internal vs External fragmentation
- Compaction

**16. Linux Basics (2-3 marks)**
- Process states in Linux
- Important commands
- File permissions

**17. Multiprocessor Systems (1-2 marks)**
- Multiprogramming vs Multiprocessing
- Cache coherence
- Scheduling in multiprocessors

**18. Real-time Operating Systems (1-2 marks)**
- Hard vs Soft real-time
- Rate monotonic scheduling
- Earliest deadline first

**19. Introduction to OS (1-2 marks)**
- OS definition and functions
- Types of OS
- Boot process

**20. Shell Scripting Basics (1-2 marks)**
- Basic commands
- Variables and control structures
- Functions

---

## Important Coding Problems

### 1. CPU Scheduling Implementation
```
c
// Round Robin Scheduling
void round_robin(Process processes[], int n, int time_quantum) {
    int remaining_burst[n];
    for(int i = 0; i < n; i++) remaining_burst[i] = processes[i].burst_time;
    
    int time = 0;
    int completed = 0;
    
    while(completed < n) {
        for(int i = 0; i < n; i++) {
            if(remaining_burst[i] > 0) {
                int execute = min(remaining_burst[i], time_quantum);
                time += execute;
                remaining_burst[i] -= execute;
                
                if(remaining_burst[i] == 0) {
                    processes[i].completion_time = time;
                    processes[i].turnaround_time = time - processes[i].arrival_time;
                    processes[i].waiting_time = processes[i].turnaround_time - processes[i].burst_time;
                    completed++;
                }
            }
        }
    }
}
```

### 2. Banker's Algorithm
```
c
// Safety Check
int is_safe(Process processes[], int n, int resources[], int max[][], int alloc[][]) {
    int need[n][3];
    for(int i = 0; i < n; i++)
        for(int j = 0; j < 3; j++)
            need[i][j] = max[i][j] - alloc[i][j];
    
    int work[3];
    for(int i = 0; i < 3; i++) work[i] = resources[i];
    
    int finish[n];
    for(int i = 0; i < n; i++) finish[i] = 0;
    
    int safe_sequence[n];
    int count = 0;
    
    while(count < n) {
        int found = 0;
        for(int i = 0; i < n; i++) {
            if(!finish[i]) {
                int can_proceed = 1;
                for(int j = 0; j < 3; j++) {
                    if(need[i][j] > work[j]) {
                        can_proceed = 0;
                        break;
                    }
                }
                if(can_proceed) {
                    for(int j = 0; j < 3; j++)
                        work[j] += alloc[i][j];
                    safe_sequence[count++] = i;
                    finish[i] = 1;
                    found = 1;
                }
            }
        }
        if(!found) return 0; // Not safe
    }
    return 1; // Safe
}
```

### 3. Page Replacement (LRU)
```
c
int lru_replace(int frames[], int n, int page, int counter[]) {
    for(int i = 0; i < n; i++) {
        if(frames[i] == page) return 0; // Page hit
    }
    
    // Find LRU frame
    int lru = 0;
    for(int i = 1; i < n; i++) {
        if(counter[i] < counter[lru]) lru = i;
    }
    
    frames[lru] = page;
    return 1; // Page fault
}
```

### 4. Producer-Consumer with Semaphores
```
c
semaphore mutex = 1;
semaphore empty = N;
semaphore full = 0;

void producer() {
    while(1) {
        // Produce item
        wait(empty);
        wait(mutex);
        // Add to buffer
        signal(mutex);
        signal(full);
    }
}

void consumer() {
    while(1) {
        wait(full);
        wait(mutex);
        // Remove from buffer
        signal(mutex);
        signal(empty);
        // Consume item
    }
}
```

### 5. Dining Philosophers
```
c
semaphore forks[5] = {1,1,1,1,1};

void philosopher(int i) {
    while(1) {
        think();
        wait(forks[i]);
        wait(forks[(i+1)%5]);
        eat();
        signal(forks[i]);
        signal(forks[(i+1)%5]);
    }
}
```

---

## Recommended Books and Free Resources

### Text Books

1. **Operating System Concepts by Silberschatz, Galvin, Gagne**
   - Most comprehensive textbook
   - Known as "The Bible of OS"
   - Excellent for theory and concepts

2. **Modern Operating Systems by Andrew Tanenbaum**
   - Clear explanation of concepts
   - Includes practical examples
   - Good for beginners

3. **Operating System Principles by Stallings**
   - Good balance of theory and practice
   - Includes recent OS topics
   - Excellent for GATE preparation

4. **Linux Kernel Development by Robert Love**
   - Best for Linux internals
   - Detailed explanation of Linux
   - Practical approach

### Reference Books for GATE

1. **Operating System: A Concepts-based Approach by Dhamdhere**
   - Good for concept clarity
   - Good collection of problems

2. **Operating System by PK Soni**
   - Often used in Indian engineering colleges
   - Good for university exams

### Free Online Resources

1. **NPTEL - Operating System Lectures**
   - Prof. Dr. Chester Rebeiro, IIT Madras
   - Excellent video lectures
   - Free at nptel.ac.in

2. **GeeksforGeeks OS Articles**
   - Comprehensive articles
   - Interview questions
   - Practice problems

3. **MIT OCW - Operating System Engineering**
   - Advanced topics
   - Research-oriented

4. **Linux Command Line Tutorial**
   - Linuxjourney.com
   - Explainshell.com

5. **OS Simulation Tools**
   - JBird: Java-based CPU scheduler simulator
   - Page replacement algorithm visualizers
   - Banker's algorithm online simulators

### Practice Websites

1. **GeeksforGeeks**
   - OS MCQs
   - Interview questions
   - Practice problems

2. **IndiaBIX**
   - Technical interview questions
   - Aptitude questions

3. **LeetCode**
   - System design problems
   - Concurrency problems

---

## Weekly Revision Plan

### Week 1-4 Revision Checklist

**Week 1: Introduction and OS Structure**
- [ ] OS definition and functions
- [ ] Types of OS
- [ ] System calls
- [ ] OS architectures

**Week 2: Process Management**
- [ ] Process vs Program
- [ ] PCB structure
- [ ] Process states
- [ ] fork(), exec(), wait()
- [ ] Threads vs Processes

**Week 3: CPU Scheduling**
- [ ] Scheduling criteria
- [ ] FCFS, SJF, Priority, RR
- [ ] Algorithm comparisons
- [ ] Numerical problem solving

**Week 4: Synchronization**
- [ ] Critical section problem
- [ ] Semaphores and mutex
- [ ] Classical problems

### Week 5-8 Revision Checklist

**Week 5: Deadlock**
- [ ] Four conditions
- [ ] Banker's algorithm
- [ ] Resource allocation graph

**Week 6: Memory Management**
- [ ] Paging concepts
- [ ] Address translation
- [ ] Page tables
- [ ] TLB

**Week 7: Virtual Memory**
- [ ] Demand paging
- [ ] Page replacement
- [ ] Thrashing

**Week 8: File Systems**
- [ ] File allocation
- [ ] Disk scheduling
- [ ] Directory implementation

### Week 9-12 Revision Checklist

**Week 9-10: Advanced Topics**
- [ ] I/O systems
- [ ] Protection and security
- [ ] Linux internals

**Week 11: Shell Scripting**
- [ ] Variables and control structures
- [ ] Functions
- [ ] Automation scripts

**Week 12: Final Revision**
- [ ] Important formulas
- [ ] Diagram practice
- [ ] Interview questions
- [ ] GATE problems

---

## Mini Projects and Final Major Project

### Mini Project List

1. **Process Scheduler Simulator** (Day 56)
   - Implement FCFS, SJF, Priority, RR
   - Calculate metrics

2. **Banker's Algorithm** (Day 57)
   - Deadlock avoidance
   - Safe sequence finder

3. **Page Replacement Simulator** (Day 58)
   - FIFO, LRU, Optimal
   - Visual demonstration

4. **Producer-Consumer** (Day 59)
   - Thread-based
   - Semaphore synchronization

5. **Dining Philosophers** (Day 60)
   - Multiple solutions
   - Deadlock demonstration

### Final Major Project: Operating System Kernel Simulation

**Project Title:** Comprehensive OS Concepts Simulator

**Description:**
Create a complete simulation of an operating system demonstrating:

1. **Process Management Module**
   - Process creation and termination
   - PCB simulation
   - State transitions

2. **CPU Scheduling Module**
   - Multiple scheduling algorithms
   - Performance metrics
   - Gantt chart generation

3. **Memory Management Module**
   - Paging simulation
   - Page replacement algorithms
   - Address translation

4. **File System Module**
   - File operations
   - Directory structure
   - Disk scheduling

5. **Synchronization Module**
   - Producer-consumer
   - Readers-writers
   - Dining philosophers

**Implementation:**
- Use C or C++ for core implementation
- Use GTK or Qt for GUI (optional)
- Include proper documentation

**Evaluation Criteria:**
- Correctness of implementation
- Code quality and documentation
- User interface
- Features implemented
- Performance

---

## Concept Clarity Checkpoints

### Checkpoint 1: Process vs Thread
- [ ] Can explain the difference clearly
- [ ] Can draw process/thread diagrams
- [ ] Can solve numerical on fork()

### Checkpoint 2: CPU Scheduling
- [ ] Can draw Gantt charts for all algorithms
- [ ] Can calculate turnaround/waiting time
- [ ] Can compare algorithms

### Checkpoint 3: Synchronization
- [ ] Can solve producer-consumer
- [ ] Can explain semaphore operations
- [ ] Can identify race conditions

### Checkpoint 4: Deadlock
- [ ] Can state all four conditions
- [ ] Can apply Banker's algorithm
- [ ] Can draw RAG

### Checkpoint 5: Memory Management
- [ ] Can do address translation
- [ ] Can solve page replacement problems
- [ ] Can calculate TLB effective access time

---

## Weekly Self-Tests

### Week 1 Self-Test

1. What are the main functions of an OS?
2. Explain the boot process.
3. What is the difference between system call and API?
4. Draw the layered architecture of OS.
5. What are the types of OS? Explain briefly.

### Week 2 Self-Test

1. What is PCB? List its components.
2. Draw and explain the process state diagram.
3. What happens when fork() is called?
4. Explain user threads vs kernel threads.
5. What is zombie process?

### Week 3 Self-Test

1. Calculate average waiting time for given processes using SJF.
2. Explain Round Robin scheduling with example.
3. What is convoy effect?
4. Compare all scheduling algorithms.
5. What is response time?

### Week 4 Self-Test

1. What is critical section? Requirements?
2. Solve producer-consumer using semaphores.
3. Explain dining philosophers problem.
4. What is the difference between mutex and semaphore?
5. What is monitor?

### Week 5 Self-Test

1. State and explain four necessary conditions for deadlock.
2. Apply Banker's algorithm to check if system is safe.
3. Draw Resource Allocation Graph.
4. What is the difference between prevention and avoidance?
5. How to recover from deadlock?

### Week 6 Self-Test

1. Calculate page table size for given system.
2. Explain TLB with effective access time calculation.
3. What is internal vs external fragmentation?
4. Explain multi-level page table.
5. Difference between paging and segmentation.

### Week 7 Self-Test

1. Solve page replacement problem using LRU.
2. What is Belady's anomaly?
3. Explain demand paging.
4. What is thrashing?
5. Calculate effective access time with page fault.

### Week 8 Self-Test

1. Compare file allocation methods.
2. Calculate seek time for SCAN algorithm.
3. Explain free space management.
4. What is inode?
5. Compare disk scheduling algorithms.

---

## Conclusion

This comprehensive 90-day roadmap covers all essential topics in Operating Systems for B.Tech CSE students. Follow this roadmap systematically:

1. **Month 1**: Build strong foundations in process management, CPU scheduling, and synchronization
2. **Month 2**: Master deadlock handling and memory management concepts
3. **Month 3**: Cover advanced topics and prepare for interviews/GATE

Remember:
- Practice coding regularly
- Solve numerical problems daily
- Draw diagrams repeatedly
- Revise weekly
- Take mock tests in final weeks

Good luck with your Operating Systems journey!

---

