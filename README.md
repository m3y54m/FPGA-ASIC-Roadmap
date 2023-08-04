# FPGA / ASIC Engineering Roadmap

**🚧 Under Construction!**

According to the feedback I received for the [Embedded Systems Engineering Roadmap](https://github.com/m3y54m/Embedded-Engineering-Roadmap) and due to my own interest, I want to create a separate roadmap specifically for FPGA / ASIC design in this repository. 

**⚠️ Disclaimer:** The contents of this repository comprise a compilation of information gathered from diverse sources for the purpose of designing the roadmap. Currently, no refinement or selection has been conducted on this information. **If you require a roadmap immediately, the content in this repository is not yet suitable for your use.** However, if you are an expert or experienced individual in the field of FPGA and ASIC design, I kindly request your comments and suggestions on this roadmap.

**What topics should be included in the FPGA / ASIC design roadmap?**

**What are the best resources you know to learn each topic in the roadmap?**

Feel free to [open an issue](https://github.com/m3y54m/FPGA-ASIC-Roadmap/issues) or [make a pull request](https://github.com/m3y54m/FPGA-ASIC-Roadmap/pulls) and express your ideas.

The first step to building a roadmap is to gather information, categorize it under different titles, and determine the importance of each title. So I started [a discussion about the roadmap](https://www.reddit.com/r/FPGA/comments/15g64oj/fpga_asic_design_roadmap/?utm_source=share&utm_medium=web2x&context=3) on Reddit:

I received a [comment](https://www.reddit.com/r/FPGA/comments/15g64oj/comment/juir34n/?utm_source=share&utm_medium=web2x&context=3) from [u/No_Delivery_1049](https://www.reddit.com/user/No_Delivery_1049/) that could serve as a good guidline:

## Draft Roadmap

### Implementation Engineer

As an FPGA (Field Programmable Gate Array) implement engineer, there are several important topics to be well-versed in:

#### Implementation Engineer

#### 1.  Hardware Description Languages (HDLs):

Knowledge of VHDL and/or Verilog is crucial as they're commonly used to design and describe digital circuits.
    
#### 2.  FPGA Design Methodologies:

Understanding of various FPGA design techniques and best practices is important.

FPGA design methodologies encompass a broad range of techniques and strategies used in the process of designing and implementing digital logic on FPGA devices. Here are some key methods:

-  **RTL Design**:

Register Transfer Level (RTL) design is a method where the digital system is described at a high level in terms of data flow between registers and the logical operations performed on the data. This allows the designer to focus on the logic functionality and data flow, rather than the specifics of how each gate is connected.
    
-  **High-Level Synthesis (HLS)**:

HLS is a design methodology where the digital system is described in a high-level programming language such as C or C++, and then automatically converted into RTL code by an HLS tool. This approach can be faster and easier than writing RTL code directly, especially for complex algorithms.
    
-  **IP Core Based Design**:

IP (Intellectual Property) cores are pre-designed circuit blocks that can be reused in multiple designs. Using IP cores can significantly speed up the design process and improve the reliability of the design, since the IP cores have been pre-verified.
    
-  **Hardware-Software Co-Design**:

In many FPGA applications, a portion of the system functionality is implemented in software running on an embedded processor, while other portions are implemented in custom hardware on the FPGA. Hardware-software co-design involves designing the hardware and software components together to achieve the best overall system performance.
    
-  **Design for Test (DFT)**:

This is a design methodology where testability features are added to the hardware design to make it easier to test and debug. This might include adding scan chains or built-in self-test (BIST) capabilities.
    
-  **Timing-Driven Design**:

This design methodology prioritizes meeting timing constraints. This may involve strategies such as pipelining to increase clock speed, carefully partitioning the design to reduce routing congestion, or using timing constraints files to guide the place-and-route process.
    
-  **Resource-Optimized Design**:

This involves making the most efficient use of FPGA resources such as logic blocks, DSP blocks, and memory blocks. It might involve strategies such as sharing resources between multiple functions, or optimizing the logic to reduce the number of logic blocks used.

These methodologies are not mutually exclusive and can often be used together in the same design. The appropriate methodology to use depends on the specific design goals and constraints.

#### 3.  Digital System Design:

Fundamental concepts in digital system design like logic gates, finite-state machines, and memory architectures.
    
#### 4.  Computer Architecture:

Deep understanding of how CPUs and memory systems work. This can be extended to specialized architectures, such as Graphics Processing Units (GPUs) or custom accelerator designs.
    
#### 5.  Timing Analysis:

Proficiency in handling setup and hold times, clock domain crossings, and other timing-related issues.
    
#### 6.  High-Level Synthesis (HLS):

Knowledge of HLS tools that convert C/C++ descriptions into HDL code is beneficial.
    
#### 7.  Embedded Systems:

Understanding of embedded system design, including both hardware and software aspects.
    
#### 8.  Signal Processing:

Depending on the application, an understanding of digital signal processing concepts can be very useful.
    
#### 9.  Power and Thermal Management:

Techniques to optimize the power consumption and manage heat dissipation.
    
#### 10.  Software Development Skills:

Including proficiency in languages such as C/C++, Python, and knowing how to work with software drivers for hardware interfaces.
    
#### 11.  Test and Debugging Techniques:

Knowledge of simulation tools, testbenches, and hardware debugging techniques.
    
#### 12.  FPGA Toolchains:

Understanding of specific FPGA toolchains like Xilinx Vivado, Intel Quartus, etc.
    
#### 13.  Version Control Systems:

Experience with version control systems like Git is often necessary for collaborative work.

### Verification Engineer

The other side of the coin is the verification engineer they play a crucial role in the development of hardware and software systems, ensuring the design meets the specified requirements. Here are several important subjects and topics that a Verification Engineer should know:

#### 1.  Hardware Description Languages (HDLs):

Verification engineers should be well-versed in VHDL and/or Verilog.
    
#### 2.  Hardware Verification Languages (HVLs):

These include SystemVerilog, which is commonly used for hardware verification, and others like Property Specification Language (PSL).
    
#### 3.  Understanding of Digital and Computer Architecture:

A strong grasp of digital electronics and computer architecture is necessary in order to understand the systems being verified.
    
#### 4.  Testbench Creation:

Verification engineers must know how to develop testbenches to simulate and verify the functionality and performance of a design.
    
#### 5.  SystemVerilog Assertions and Functional Coverage:

These are key for ensuring the design behaves as expected under all conditions, and for making sure all important scenarios are tested.
    
#### 6.  Universal Verification Methodology (UVM):

This is an industry-standard methodology for verification of hardware designs.
    
#### 7.  Formal Verification Methods:

Including equivalence checking and model checking.
    
#### 8.  Debugging and Troubleshooting:

These skills are critical for identifying and resolving issues that come up during verification.
    
#### 9.  Scripting Languages:

Languages such as TCL, Python, Perl, or Shell scripting are often used to automate tasks in the verification process.
    
#### 10.  Version Control Systems:

Familiarity with systems like Git or Subversion is important for managing code and tracking changes.
    
#### 11.  Industry Standards:

Familiarity with relevant industry standards can be important, especially in fields like telecommunications or automotive.
    
#### 12.  Familiarity with FPGA and ASIC Design Flow:

Understanding the overall process of design, from specification to synthesis and place-and-route, is helpful in order to interface effectively with the design team.

**Both implementation and verification engineer need to be aware of requirements, architecture and interconnect standards and interfaces.**



