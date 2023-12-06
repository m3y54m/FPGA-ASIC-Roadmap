# FPGA / ASIC Engineering Roadmap

**🚧 WORK IN PROGRESS!**

According to the positive feedback I received for the [Embedded Systems Engineering Roadmap](https://github.com/m3y54m/Embedded-Engineering-Roadmap) and due to my own interest in FPGA, I want to create a separate roadmap specifically for FPGA design in this repository. 

> [!WARNING]  
> The contents in this repository are gathered from various sources to create a roadmap. At present, no sorting or filtering has been done on this information. **If you require a complete roadmap now, the contents in this repository might not yet suitable for you.**

## Contribution

If you are an expert or experienced individual in the field of FPGA and ASIC design, I kindly request for comments and suggestions on this roadmap.

**What topics should be included in the FPGA / ASIC design roadmap?**

**What are the best resources you know to learn each topic in the roadmap?**

Feel free to [open an issue](https://github.com/m3y54m/FPGA-ASIC-Roadmap/issues) or [make a pull request](https://github.com/m3y54m/FPGA-ASIC-Roadmap/pulls) and express your ideas.

The first step to building a roadmap is to gather information, categorize it under different titles, and determine the importance of each title. So I started [a discussion about the roadmap](https://www.reddit.com/r/FPGA/comments/15g64oj/fpga_asic_design_roadmap/?utm_source=share&utm_medium=web2x&context=3) on Reddit.

## Learning Resources

- [What are FPGAs?](https://hackaday.io/project/27550-the-hobbyists-guide-to-fpgas/log/68114-what-are-fpgas)
- [Introduction to FPGA - Shawn Hymel (YouTube Playlist)](https://youtube.com/playlist?list=PLEBQazB0HUyT1WmMONxRZn9NmQ_9CIKhb)
- [FPGA 101 - Nandland](https://nandland.com/fpga-101/)
- [Nandland (YouTube Channel)](https://www.youtube.com/@Nandland)
- [FPGA 4 Fun](https://www.fpga4fun.com/)
- [EDA Playground](https://www.edaplayground.com/)
- [FPGAs for Beginners (YouTube Channel)](https://www.youtube.com/@FPGAsforBeginners)
- [asic-world.com](https://www.asic-world.com/)
- [Project F - FPGA Tutorials](https://projectf.io/tutorials/)
- [Learning FPGA, yosys, nextpnr, and RISC-V](https://github.com/BrunoLevy/learn-fpga)
- [Doulos - Global Independent Leaders in Design and Verification KnowHow](https://www.doulos.com/)
- [Home of MicroZed Chronicles, Blogs on AMD, Intel, Lattice FPGA](https://www.adiuvoengineering.com/)
- [Tiny Tapeout: from idea to chip design in minutes!](https://tinytapeout.com/)
- [Coursera - FPGA Design for Embedded Systems Specialization](https://www.coursera.org/specializations/fpga-design)
- [Udemy – FPGA Embedded Design, Part 1 - Verilog](https://www.udemy.com/course/fpga-embedded-design-verilog/)
- [Udemy – FPGA Embedded Design, Part 2 - Basic FPGA Training](https://www.udemy.com/course/fpga-embedded-design-fpgas/)
- [Udemy – FPGA Embedded Design, Part 3 - EDA Tools](https://www.udemy.com/course/fpga-embedded-design-eda-tools/)
- [Udemy – FPGA Embedded Design, Part 4 - Microprocessor Design](https://www.udemy.com/course/fpga-embedded-design-cpu/)
  
## Projects

- [AMD Based FPGA Projects - Whitney Knitter](https://hackster.io/whitney-knitter)
- [AMD Based FPGA Projects - Adam Taylor](https://www.hackster.io/adam-taylor)
- [RISC-V Single Cycle Core in Verilog](https://www.youtube.com/playlist?list=PL5AmAh9QoSK7Fwk9vOJu-3VqBng_HjGFc)
- [SPI Project in FPGA - Ambient Light Sensor](https://youtube.com/playlist?list=PLnAoag7Ew-vq5kOyfyNN50xL718AtLoCQ)

## Roadmap

### Common Skills

#### Hardware Description Languages (HDLs):

Knowledge of VHDL and/or Verilog is crucial as they're commonly used to design and describe digital circuits.

- [VHDLwhiz - Basic VHDL Tutorials](https://vhdlwhiz.com/basic-vhdl-tutorials/)
- [VHDLwhiz.com (YouTube Channel)](https://www.youtube.com/@VHDLwhiz)
- [HDLBits — Verilog Practice](https://hdlbits.01xz.net/wiki/Main_Page)
- [FPGA designs with Verilog](https://verilogguide.readthedocs.io/en/latest/index.html)

#### Digital System Design

Fundamental concepts in digital system design like logic gates, finite-state machines, and memory architectures.

- [Tiny Tapeout > Digital Design Guide](https://tinytapeout.com/digital_design/)
- [FPGA Fundamentals - Nandland](https://nandland.com/fpga-101/)
- [Digital Design - Morris Mano, Michael Ciletti](https://a.co/d/c3tBaoc)
- [Digital Design and Computer Architecture: ARM Edition -  Sarah Harris, David Harris](https://a.co/d/4otoVvI)
- [Digital Design and Computer Architecture: RISC-V Edition -  Sarah Harris, David Harris](https://a.co/d/61l7Jtb)
- [Digital Fundamentals - Thomas L. Floyd](https://a.co/d/2lgJKNX)

#### Computer Architecture

Deep understanding of how CPUs and memory systems work. This can be extended to specialized architectures, such as Graphics Processing Units (GPUs) or custom accelerator designs.

- [Computer Organization and Design: ARM Edition -  David A. Patterson, John L. Hennessy](https://a.co/d/8YPUXG7)
- [Digital Design and Computer Architecture: ARM Edition -  Sarah Harris, David Harris](https://a.co/d/4otoVvI)
- [Digital Design and Computer Architecture: RISC-V Edition -  Sarah Harris, David Harris](https://a.co/d/61l7Jtb)
- [Build an 8-bit computer from scratch](https://eater.net/8bit/)

#### Test and Debugging Techniques

Knowledge of simulation tools, testbenches, and hardware debugging techniques.

- [Debugging with Speed and Precision: Mastering the Art of FPGA Debugging](https://fpgainsights.com/fpga/debugging-with-speed-and-precision-mastering-the-art-of-fpga-debugging/)
    
#### Version Control

Familiarity with systems like Git or Subversion is important for managing code and tracking changes.

- [Git Tutorial for Beginners: Learn Git in 1 Hour](https://www.youtube.com/watch?v=8JJ101D3knE)
- [Git for Professionals Tutorial - Tools & Concepts for Mastering Version Control with Git](https://www.youtube.com/watch?v=Uszj_k0DGsg)
- [Apache® Subversion®](https://subversion.apache.org/)

#### Familiarity with FPGA and ASIC Design Flow

Understanding the overall process of design, from specification to synthesis and place-and-route, is helpful in order to interface effectively with the design team.

- [A Hands-On Guide to Designing Embedded Systems - Adam Taylor, Dan Binnun, Saket Srivastava](https://www.amazon.com/Hands-Guide-Designing-Embedded-Systems/dp/1630816833)
- [Understanding FPGA Programming and Design Flow](https://hardwarebee.com/understanding-fpga-programming-and-design-flow/)
- [ASIC Design Flow in VLSI Engineering Services – A Quick Guide](https://www.einfochips.com/blog/asic-design-flow-in-vlsi-engineering-services-a-quick-guide/)

**Both implementation and verification engineer need to be aware of requirements, architecture and interconnect standards and interfaces.**

----------------

### Implementation Engineer

As an FPGA (Field Programmable Gate Array) implement engineer, there are several important topics to be well-versed in:

#### FPGA Design Methodologies:

Understanding of various FPGA design techniques and best practices is important.

FPGA design methodologies encompass a broad range of techniques and strategies used in the process of designing and implementing digital logic on FPGA devices. Here are some key methods:

##### RTL Design

Register Transfer Level (RTL) design is a method where the digital system is described at a high level in terms of data flow between registers and the logical operations performed on the data. This allows the designer to focus on the logic functionality and data flow, rather than the specifics of how each gate is connected.

- [Understanding RTL Design: Building the Foundation of Digital Systems](https://www.linkedin.com/pulse/understanding-rtl-design-building-foundation-digital-systems-pandey/)

##### High-Level Synthesis (HLS)

HLS is a design methodology where the digital system is described in a high-level programming language such as C or C++, and then automatically converted into RTL code by an HLS tool. This approach can be faster and easier than writing RTL code directly, especially for complex algorithms.

- [High-Level Synthesis Made Easy: Synthesizing Behavioral Descriptions directly into Hardware Circuits](https://www.hlsbook.com/)
- [High-Level Synthesis Blue Book](https://hlsbluebook.org/)
- [Vitis HLS — Vitis™ Tutorials](https://xilinx.github.io/Vitis-Tutorials/2021-1/build/html/docs/Getting_Started/Vitis_HLS/Getting_Started_Vitis_HLS.html)
    
##### IP Core Based Design

IP (Intellectual Property) cores are pre-designed circuit blocks that can be reused in multiple designs. Using IP cores can significantly speed up the design process and improve the reliability of the design, since the IP cores have been pre-verified.

- [Basics of core-based FPGA design](https://www.embedded.com/basics-of-core-based-fpga-design-part-1-core-types-trade-offs/)
- [IP Cores For FPGA Designs](https://www.electronicsforu.com/electronics-projects/electronics-design-guides/ip-cores-fpga-designs)
- [So you want to Design a FPGA IP Core!](https://www.hackster.io/adam-taylor/so-you-want-to-design-a-fpga-ip-core-56e0f1)

##### Hardware-Software Co-Design

In many FPGA applications, a portion of the system functionality is implemented in software running on an embedded processor, while other portions are implemented in custom hardware on the FPGA. Hardware-software co-design involves designing the hardware and software components together to achieve the best overall system performance.

- [Hardware/Software Co-Design: The Five Core Principles](https://www.electronicdesign.com/technologies/eda/article/21267771/recogni-hardwaresoftware-codesign-the-five-core-principles)

##### Design for Test (DFT)

This is a design methodology where testability features are added to the hardware design to make it easier to test and debug. This might include adding scan chains or built-in self-test (BIST) capabilities.

- [DESIGN FOR TEST](https://www.faststreamtech.com/services/semiconductor-design/design-for-test/)

##### Timing-Driven Design

This design methodology prioritizes meeting timing constraints. This may involve strategies such as pipelining to increase clock speed, carefully partitioning the design to reduce routing congestion, or using timing constraints files to guide the place-and-route process.
    
##### Resource-Optimized Design

This involves making the most efficient use of FPGA resources such as logic blocks, DSP blocks, and memory blocks. It might involve strategies such as sharing resources between multiple functions, or optimizing the logic to reduce the number of logic blocks used.

These methodologies are not mutually exclusive and can often be used together in the same design. The appropriate methodology to use depends on the specific design goals and constraints.

#### Timing Analysis

Proficiency in handling setup and hold times, clock domain crossings, and other timing-related issues.
    
#### Embedded Systems

Understanding of embedded system design, including both hardware and software aspects.
    
#### Signal Processing

Depending on the application, an understanding of digital signal processing concepts can be very useful.

- [controlpaths - Blogs in control and signal processing](https://www.controlpaths.com/)
    
#### Power and Thermal Management

Techniques to optimize the power consumption and manage heat dissipation.
    
#### Software Development Skills

Including proficiency in languages such as C/C++, Python, and knowing how to work with software drivers for hardware interfaces.
    
#### FPGA Toolchain

Understanding of specific FPGA toolchains like Xilinx Vivado, Intel Quartus, etc.

----------

### Verification Engineer

The other side of the coin is the verification engineer they play a crucial role in the development of hardware and software systems, ensuring the design meets the specified requirements. Here are several important subjects and topics that a Verification Engineer should know:
    
#### Hardware Verification Languages (HVLs)

These include SystemVerilog, which is commonly used for hardware verification, and others like Property Specification Language (PSL).
    
#### Testbench Creation

Verification engineers must know how to develop testbenches to simulate and verify the functionality and performance of a design.
    
#### SystemVerilog Assertions and Functional Coverage

These are key for ensuring the design behaves as expected under all conditions, and for making sure all important scenarios are tested.

- [SystemVerilog Tutorial](https://www.asic-world.com/systemverilog/tutorial.html)
- [SystemVerilog for Verification - Chris Spear , Greg Tumbush](https://link.springer.com/book/10.1007/978-1-4614-0715-7)
    
#### Universal Verification Methodology (UVM)

This is an industry-standard methodology for verification of hardware designs.

- [UVM (Standard Universal Verification Methodology)](https://www.accellera.org/downloads/standards/uvm)
- [UVM 1.2 User Guide](http://www.accellera.org/images//downloads/standards/uvm/uvm_users_guide_1.2.pdf)
- [UVM Guide for Beginners](https://colorlesscube.com/uvm-guide-for-beginners/)
- [The UVM Primer: A Step-by-Step Introduction to the Universal Verification Methodology - Ray Salemi](https://www.amazon.com/dp/0974164933?_encoding=UTF8&psc=1&ref_=cm_sw_r_cp_ud_dp_SFYBP2WRG9PGJYY6RBEE)
    
#### Formal Verification Methods

Including equivalence checking and model checking.

- [Verilog, Formal Verification and Verilator Beginner's Tutorial](https://zipcpu.com/tutorial/)
- [11 Myths About Formal Verification](https://www.electronicdesign.com/technologies/eda/article/21807132/11-myths-about-formal-verification)

#### Scripting Languages

Languages such as TCL, Python, Perl, or Shell scripting are often used to automate tasks in the verification process.

- [Why you need to learn Tcl](https://vhdlwhiz.com/why-you-need-to-learn-tcl/)
- [Top 10 Tips for efficient Perl Scripting for Chip Designers](https://www.design-reuse.com/articles/20613/perl-scripting-chip-design.html)
- [The Python for Verification Series](https://verificationacademy.com/news/the-python-for-verification-series)
- [cocotb, a coroutine based cosimulation library for writing VHDL and Verilog testbenches in Python](https://www.cocotb.org)

#### Industry Standards

Familiarity with relevant industry standards can be important, especially in fields like telecommunications or automotive.
    
## Acknowledgement

Special thanks to [u/No_Delivery_1049](https://www.reddit.com/user/No_Delivery_1049/) the reddit user who made this [comment](https://www.reddit.com/r/FPGA/comments/15g64oj/comment/juir34n/?utm_source=share&utm_medium=web2x&context=3) that served as the base of this roadmap.
