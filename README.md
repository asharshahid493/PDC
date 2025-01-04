# Python Basics and Parallel Programming Examples

This repository contains various Python scripts demonstrating basic functionality, parallel programming, multithreading, multiprocessing, inter-process communication (IPC), and MPI (Message Passing Interface). The scripts are organized into two main categories: basic Python scripts and advanced parallel programming examples.

## Folder Structure

### Basics Folder

- **Code 1**: Basic Calculator using Python  
- **Code 2**: Python Code Implementing List, Dictionary, and Tuples  
- **Code 3**: Function to Calculate Sum  
- **Code 4**: Using Classes and Objects  

### Chapter 1: Parallel Programming Basics

- **bank.py**: Demonstrates multithreading to perform deposit and withdrawal operations on a shared balance with execution time measurement.  
- **data_parallelism.py**: Uses `ThreadPoolExecutor` to execute two tasks concurrently.  
- **do_something.py**: Defines a function that generates random numbers and adds them to a list for a specified count.  
- **fibonacci.py**: Calculates the 35th Fibonacci number using multiple threads and measures execution time.  
- **hello.py**: Demonstrates data-parallel vector addition with NumPy.  
- **ipc.py**: Shows inter-process communication with a queue, with a producer adding items and a consumer retrieving them.  
- **mpi.py**: Uses MPI for communication between processes (process 0 sends data to process 1).  
- **multiprocessing.py**: Compares performance of multiprocessing and multithreading for generating random numbers.  
- **parallelization.py**: Performs parallel vector addition using threads.  
- **process_creation.py**: Demonstrates multiprocessing to calculate square and cube of a number concurrently.  
- **shared_mem.py**: Uses threading with a lock to manage shared balance for deposits and withdrawals.  
- **synchronization.py**: Demonstrates semaphore usage to control access to a shared resource.  

### Chapter 2: Advanced Synchronization and Threading

- **barrier.py**: Simulates a race with three runners using threads and a barrier to synchronize arrival.  
- **condition.py**: Implements a producer-consumer problem using a condition variable for synchronization.  
- **event.py**: Implements a simple producer-consumer problem using threading and an event.  
- **mythreadclass.py**: Creates and runs 9 threads, each with random durations, and ensures the main thread waits for them.  
- **mythreadclass_lock.py**: Uses a lock to ensure mutual exclusion in multithreaded tasks.  
- **mythreadclass_lock2.py**: Simulates random durations in threads while ensuring mutual exclusion using a lock.  
- **rlock.py**: Demonstrates the use of reentrant locks with threads for adding/removing items from a shared resource.  
- **semaphore.py**: Uses semaphores to synchronize producer-consumer threads.  
- **threaddefinition.py**: Creates 10 threads, each calling a function with a unique thread number.  
- **thread_determine.py**: Creates three threads that execute different functions and print messages before and after sleeping.  
- **thread_name_and_processes.py**: Creates two threads, each printing the thread name and process ID.  
- **threading_with_queue.py**: Demonstrates thread synchronization using a queue with multiple consumers and a single producer.  

### Inter-Process Communication (IPC) and Process Management

- **communicating_with_pipe.py**: Demonstrates inter-process communication using Pipe for data exchange.  
- **communicating_with_queue.py**: Uses Queue for IPC, where multiple producer-consumer processes exchange data.  
- **derom.py**: Demonstrates specific multiprocessing/threading functionality (context-specific use).  
- **killing_processes.py**: Manages and terminates processes using the `multiprocessing` module.  
- **myfunc.py**: Defines a simple function for multiprocessing or threading demonstrations.  
- **naming_processes.py**: Assigns custom names to processes for better debugging and monitoring.  
- **process_in_subclass.py**: Shows how to subclass the `Process` class and define custom behavior.  
- **process_pool.py**: Demonstrates the use of a process pool for parallel task execution.  
- **processes_barrier.py**: Uses the Barrier synchronization primitive for process synchronization.  
- **run_background_processes.py**: Demonstrates running background processes.  
- **run_background_processes_no_daemons.py**: Demonstrates running non-daemon background processes.  
- **spawning_processes.py**: Demonstrates spawning new processes using `multiprocessing`.  
- **spawning_processes_namespace.py**: Shows process spawning with shared namespaces for interprocess collaboration.  

### MPI Communication and Parallel Computation

- **alltoall.py**: Demonstrates the `Alltoall` communication pattern in MPI, where each process sends and receives data from all other processes.  
- **broadcast.py**: Demonstrates the `Broadcast` communication operation in MPI for distributing shared data.  
- **deadlockproblems.py**: Illustrates potential deadlock scenarios and strategies to avoid them in parallel programs.  
- **point_to_point_comm.py**: Demonstrates point-to-point communication in MPI between two processes.  
- **reduction.py**: Shows the `Reduction` operation in MPI, where data from multiple processes is aggregated into a single result.  
- **scatter.py**: Demonstrates the `Scatter` communication pattern in MPI, distributing data from one process to all others.  
- **virtualtopology.py**: Creates virtual topologies in MPI for optimized communication in parallel programs.  

### Concurrent Futures and Asynchronous Programming

- **concurrent_futures_pooling.py**: Demonstrates task pooling with the `concurrent.futures` module for parallel execution.  
- **coroutine.py**: Shows how coroutines can be used in Python with the `asyncio` module for asynchronous execution.  
- **dealing.py**: Demonstrates managing tasks in an asynchronous environment with handling exceptions and cancellations.  
- **event_loops.py**: Demonstrates the concept of event loops for asynchronous task management in `asyncio`.  
- **manipulating_task.py**: Demonstrates manipulation of asynchronous tasks, including creation, cancellation, and awaiting.  

## Setup and Installation

To run the examples:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/python-parallel-examples.git
