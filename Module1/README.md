# Module 1

---

## Differences between CPU, MCU and an Embedded System

### CPU (Central Processing Unit)

The microprocessor, also known as a central processing unit or CPU, is the central core of an embedded system. It is a multipurpose, clock driven, programmable electronic device designed to perform arithmetic and logic operations using an arithmetic logic unit, or ALU. It usually performs the instruction cycle of fetching, decoding and executing.

The microprocessor also communicates with other external components with a memory unit via a 
memory interface, and can perform I/O operations based on specific instructions. 

![CPU](./images/cpu.png)

### MCU

A microcontroller unit or MCU consists of a microprocessor plus additional peripheral components such as memory blocks, digital I/Os, analog I/Os, timers, and other basic peripherals. 

The microprocessor is usually a single-core CPU to optimize power and cost efficiency. On-chip memory components such as random-access memory and read-only memory are also optimized for speed, cost, durability, and energy efficiency.

Additional hardware components can include a variety of input and output components, timers, interrupt structures, external buses, and so on. These are chosen based on the controller’s final purpose. All the components within a microcontroller communicate via an internal system bus. 

### Embedded System

An embedded system usually contains one or more interconnected MCUs.

Most parts of an embedded system are electrical components. However, the mechanical structure or the housing of the sensor may also provide important functionality.

The range of applications for an embedded system are enormous. For example, an embedded system can be used as a closed-loop control system to monitor and process a system state, or adjust an output to maintain a desired set point such as temperature, speed, or direction. An embedded system can take over very specialized functions as part of a larger system, such as fault handling or networking, or it could be used to step through different stages of a program, based on environment 
and system requirements

![CPU](./images/embedded-system.png)
