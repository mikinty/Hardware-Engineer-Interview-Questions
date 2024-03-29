# Embedded Questions

- What does it mean to program on "bare metal"?
  - Why do we not get exceptions and errors thrown at us for free when we work with embedded code?

## Assembly

* Explain the advantages and disadvantages of using RISC vs CISC architectures
* Explain some ways compilers optimize assembly code
* Describe why it is sometimes necessary for developers to code in assembly
* What is context switching? How do you perform it?

## Kernel

* What is an interrupt?
  * What are the different types of interrupts?
  * How would you implement an interrupt handler?
  * What are some applications of interrupts?

## Scheduling

* What is a critical section?
* What is an atomic operation and how would you implement one?
* What are race conditions?
* What is a semaphore?
* What is deadlock?
  * What are the necessary conditions for a deadlock?
  * How would you know if your system is in a deadlock?
* Describe the producer/consumer problem, and a possible solution.
* Understand the following types of scheduling, along with whether or not they can have starvation or deadlock
  * First come, first serve
  * Shortest job, first scheduled
  * Priority scheduling (each process assigned a priority)
  * Round-Robin
  * Multi-rate periodic
  * Rate Monotonic Scheduling (RMS)
    * Understand that it is an optimal static periority scheduler
    * Know the RMS Utilization Bound
    * Liu and Leyland ("Scheduling Algorithms for Multiprogramming in a Hard Real-Time Environment", JACM, 1973)
  * Earliest deadline first
  * Basic Priority Inheritance Protocol
  * Highest Locker's Priority Protocol
  * Priority Ceiling Protocol

## Peripherals

* What is MMIO (Memory Mapped I/O)?
* Explain the following methods of addressing, along with their pros and cons:
  * I2C
  * SPI
* What is a PID controller?