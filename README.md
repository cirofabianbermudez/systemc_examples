# systemc_examples

## What is SystemC?

SystemC is an ANSI standard C++ class library for system and hardware design for use by designers and architects who need to address complex systems that are a hybrid between hardware and software.

- SystemC is a C++ class library that supports design and verification of hardware and software at multiple levels of abstraction.
- SystemC provides a unified environment for architects, verification engineers and implementation engineers.


## Layared SystemC Architecture
- C++ Language Standard
- Event-driven Simulation
    - Events
    - Processes
- Structural elements
    - Modules
    - Ports
    - Interfaces
    - Channels
- Data Types
    - 4-valued logic
    - Bits and Bit Vectors
    - Arbitrary Precision Integers
    - Fixed point types
- Primitive Channels
    - Signal
    - FIFO
    - Mutex
    - Semaphores
- Methodology-Specific Libraries
    - Master/Slave library
- Layered Libraries
    - Verification library
    - TLM library

## Significant Features
Significant features of SystemC are that it:
- Facilitates modeling and verification at a high abstraction level
    - Higher abstraction means less detail means faster simulation
- Facilitates iterative module refinement from higher to lower levels
    - By separating communication specification from its implementation
- Defines a base model of computation that you can customize
    - What is a "model of computation"?

## Models of Computation
A model of computation defines the means available for modeling systems:
- The time model (i.e. none, discrete, continuous)
- The event ordering constraints (i.e. partial, global)
- The inter-process communication
- The process triggering

SystemC supports the following model of computation
- SystemC time models and event ordering
    - Untimed
    - Untimed with discrete ordered events
    - Timed with discrete ordered events
- SystemC inter-process communication
    - Based upon built in or user-defined channels (abstraction of signals)
- SystemC process activation
    - Based upon events (event-based simulation)

