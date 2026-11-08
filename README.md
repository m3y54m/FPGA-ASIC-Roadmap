# FPGA / ASIC Engineering Roadmap

This roadmap helps beginners who want to start a career in **FPGA** and **ASIC** (chip) design, and helps current practitioners broaden their skills. FPGA and ASIC engineers write the same kind of code (RTL) and share most of the fundamentals; the main differences are in the tools, the implementation flow and the cost of a mistake.

> [!TIP]
> To differentiate between the types of learning resources and the quality of their content, specific symbols are used before each item.
>
> **Resource types:**
>
> - 📘 : Books
> - 🎞️ : Videos
> - 📝 : Write-ups, articles, and blog posts
> - 🔗 : Other links that do not fit into any of the above categories
>
> **Content quality symbols:**
>
> - 👶 : Easy-to-understand and beginner-friendly resources. Refer to them if you do not have prior knowledge in a topic.
> - 💎 : Well-known references that have truly invaluable and comprehensive content. Refer to them if you want to deepen your understanding of a topic.
>
> **Topic priority** (shown under each topic in the Roadmap):
>
> - **Required** : Every engineer in the field needs it.
> - **Recommended** : Needed for most jobs or for a given specialization.
> - **Optional** : Useful in specific domains or for going deeper.

New to the field? Start with the suggested learning path below, and keep this in mind while you study:

> [!WARNING]
> You do not need to read every book and article or watch every video listed here. Study enough to understand a topic, then practice by writing and simulating real designs. Hardware design is learned by doing.

## Suggested Learning Path

1. **Learn digital logic and computer architecture.** Gates, flip-flops, finite-state machines, and how a simple CPU works: [Nand2Tetris](https://www.nand2tetris.org/), [Computation Structures](https://computationstructures.org/index.html), and the book *Digital Design and Computer Architecture* (see Digital Logic and Computer Architecture).
2. **Pick one HDL and practice small problems.** Verilog/SystemVerilog with [HDLBits](https://hdlbits.01xz.net/wiki/Main_Page), or VHDL with [VHDLwhiz](https://vhdlwhiz.com/basic-vhdl-tutorials/). Do not worry about the "best" language: the concepts transfer (see Hardware Description Languages).
3. **Set up free simulation tools.** [Icarus Verilog](https://github.com/steveicarus/iverilog) or [Verilator](https://verilator.org/guide/latest/) (or [GHDL](https://github.com/ghdl/ghdl) for VHDL) with [GTKWave](https://github.com/gtkwave/gtkwave), or simply use [EDA Playground](https://www.edaplayground.com/) in the browser (see Simulation, Testbenches and Debugging).
4. **Write clean, synthesizable RTL.** Learn state machines, registers, resets and coding style before writing big designs (see RTL Design Practices).
5. **Run the full FPGA flow on real hardware.** Synthesize, place-and-route and program a cheap board (see Getting an FPGA Board) with [Nandland](https://nandland.com/fpga-101/) or [Project F](https://projectf.io/tutorials/).
6. **Learn timing, clock domain crossing and standard interfaces.** These separate hobby designs from professional ones (see Timing Analysis and Constraints, Clock Domain Crossing and Resets, and Interfaces, Protocols and Memory).
7. **Build projects.** A UART, a VGA/HDMI display controller, a small RISC-V CPU (see Projects).
8. **Specialize.** Go deeper into implementation, verification or ASIC design.

## Learning Resources

A general collection of courses, tutorials, books and websites to get started. Resources for specific topics are listed in the [Roadmap](#roadmap) section below, and neighboring fields (electronics, RF, power electronics) are at the end of this section.

- [📝👶 What are FPGAs?](https://hackaday.io/project/27550-the-hobbyists-guide-to-fpgas/log/68114-what-are-fpgas)
- [🎞️👶 Introduction to FPGA - Shawn Hymel (YouTube Playlist)](https://youtube.com/playlist?list=PLEBQazB0HUyT1WmMONxRZn9NmQ_9CIKhb)
- [🔗👶 FPGA 101 - Nandland](https://nandland.com/fpga-101/)
- [🎞️ Nandland (YouTube Channel)](https://www.youtube.com/@Nandland)
- [🎞️👶 FPGAs for Beginners (YouTube Channel)](https://www.youtube.com/@FPGAsforBeginners)
- [📘👶 Getting Started with FPGAs - Russell Merrick (Nandland)](https://nostarch.com/gettingstartedwithfpgas)
- [📘👶 Free Range VHDL - Bryan Mealy, Fabrizio Tappero](https://github.com/fabriziotappero/Free-Range-VHDL-book)
- [🔗👶 Nand2Tetris - Build a Modern Computer from First Principles](https://www.nand2tetris.org/)
- [🎞️👶 Coursera - Digital Systems: From Logic Gates to Processors](https://www.coursera.org/learn/digital-systems)
- [🔗 MIT 6.111 - Introductory Digital Systems Laboratory](https://web.mit.edu/6.111/www/f2017/)
- [🎞️💎 Digital Design and Computer Architecture - Onur Mutlu, ETH Zürich (YouTube Channel)](https://www.youtube.com/@onurmutlulectures)
- [🔗💎 Zero to ASIC Course](https://www.zerotoasiccourse.com/)
- [🎞️ Coursera - VLSI CAD Part I: Logic](https://www.coursera.org/learn/vlsi-cad-logic)
- [🔗 asic-world.com](https://www.asic-world.com/)
- [🔗 Learn Chip Design & Verification](https://www.chipverify.com/)
- [📝👶 Verilog Tutorial - ASIC World](https://www.asic-world.com/verilog/veritut.html)
- [📝👶 Verilog Tutorial - ChipVerify](https://www.chipverify.com/verilog/verilog-tutorial)
- [🔗 Verification Academy](https://verificationacademy.com/)
- [📝 VHDL vs Verilog vs SystemVerilog: Which Hardware Language Should You Learn First for a Successful Career?](https://medium.com/@techAsthetic/vhdl-vs-verilog-vs-system-verilog-what-to-learn-first-7ff9e247ffd9)
- [🔗 Digital Electronics Deeds](https://www.digitalelectronicsdeeds.com/index.html)
- [📝👶💎 Project F - FPGA Tutorials](https://projectf.io/tutorials/)
- [🔗💎 Tiny Tapeout: from idea to chip design in minutes!](https://tinytapeout.com/)
- [📝💎 Learning FPGA, yosys, nextpnr, and RISC-V](https://github.com/BrunoLevy/learn-fpga)
- [🔗💎 Doulos - Global Independent Leaders in Design and Verification KnowHow](https://www.doulos.com/)
- [🎞️ Coursera - FPGA Design for Embedded Systems Specialization](https://www.coursera.org/specializations/fpga-design)
- [🎞️ Coursera - Computer Architecture](https://www.coursera.org/learn/comparch)
- [🎞️ Coursera - Hardware Security](https://www.coursera.org/learn/hardware-security)
- [🎞️ Udemy – FPGA Embedded Design, Part 1 - Verilog](https://www.udemy.com/course/fpga-embedded-design-verilog/)
- [🎞️ Udemy – FPGA Embedded Design, Part 2 - Basic FPGA Training](https://www.udemy.com/course/fpga-embedded-design-fpgas/)
- [🎞️ Udemy – FPGA Embedded Design, Part 3 - EDA Tools](https://www.udemy.com/course/fpga-embedded-design-eda-tools/)
- [🎞️ Udemy – FPGA Embedded Design, Part 4 - Microprocessor Design](https://www.udemy.com/course/fpga-embedded-design-cpu/)
- [🔗👶 FPGA 4 Students](https://www.fpga4student.com/)
- [🔗👶 Access an FPGA right now!](https://ps1.fpgas.online/fpgas/)
- [📝 Designing a Custom AXI Slave (Avnet PDF)](https://www.avnet.com/wcm/connect/557e3453-20d7-4737-b2a8-8afc404dc81e/designing_a_custom_axi_slave_rev1.pdf?MOD=AJPERES&ContentCache=NONE&CACHE=NONE&CVID=picU33N)
- [🔗💎 Computation Structures](https://computationstructures.org/index.html)
- [🎞️ YouTube Playlist - CMOS Digital VLSI Design](https://www.youtube.com/playlist?list=PLLy_2iUCG87Bdulp9brz9AcvW_TnFCUmM)
- [🎞️ YouTube Playlist - Basic Computer Architecture](https://www.youtube.com/playlist?list=PL1iLu2CSC9EWAo0ysorNI_nebwF6Rwkr0)
- [🎞️ YouTube Playlist - Hardware Modeling using Verilog](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBELELTSPgzYkQg3HgclQh-5)
- [🎞️ YouTube Playlist - Microprocessors and Microcontrollers](https://www.youtube.com/playlist?list=PLuv3GM6-gsE01L9yDO0e5UhQapkCPGnY3)
- [🔗 MakerCode](https://makercode.jixiao-ai.com/)
- [🔗 Logi-Code](https://logi-code.com/)
- [🔗 Sistenix](https://sistenix.com/)

### Related Fields (Optional)

Electronics, semiconductor physics, RF, power electronics and microcontrollers are not required to start with FPGA/ASIC design, but they help for board-level work, analog/mixed-signal design and chip fabrication.

- [🎞️👶 Neso Academy - Electronics & Communication](https://www.nesoacademy.org/home/Electronics%20&%20Communication)
- [🎞️ edX - MITx: Circuits and Electronics 1: Basic Circuit Analysis](https://www.edx.org/learn/circuits/massachusetts-institute-of-technology-circuits-and-electronics-1-basic-circuit-analysis)
- [🎞️ Coursera - Introduction to Electronics](https://www.coursera.org/learn/electronics)
- [🎞️ Coursera - Semiconductor Physics](https://www.coursera.org/learn/semiconductor-physics)
- [🎞️ Coursera - MOSFET](https://www.coursera.org/learn/mosfet)
- [🎞️ Coursera - Introduction to Microfabrication](https://www.coursera.org/learn/introduction-to-microfabrication)
- [🎞️ Coursera - Power Electronics Specialization](https://www.coursera.org/specializations/power-electronics)
- [🎞️ Coursera - RF MM-Wave Circuit Design](https://www.coursera.org/learn/rf-mmwave-circuit-design)
- [🎞️ Coursera - RF/Microwave Design - S-Parameter Analysis](https://www.coursera.org/learn/rfmicrowave-design---s-parameter-analysis)
- [🎞️ Coursera - RF/Microwave Design - Impedance Matching](https://www.coursera.org/learn/rfmicrowave-design---impedance-matching)
- [🎞️ Coursera - RF/Microwave Design - Antenna Design](https://www.coursera.org/learn/rfmicrowave-design---antenna-design)
- [🎞️ Coursera - Microwave Antenna](https://www.coursera.org/learn/microwave-antenna)
- [🎞️ Coursera - ARM Cortex STM32 Deep Dive: Mastering Embedded Systems](https://www.coursera.org/learn/arm-cortex-stm32-deep-dive-mastering-embedded-systems)

## Projects

Project ideas and complete open-source designs to practice on and read. Start small (blinking LEDs, a UART, a display controller) before moving on to CPUs and SoCs.

- [🔗 FPGA 4 Fun](https://www.fpga4fun.com/)
- [🔗 AMD Based FPGA Projects - Whitney Knitter](https://hackster.io/whitney-knitter)
- [🔗 AMD Based FPGA Projects - Adam Taylor](https://www.hackster.io/adam-taylor)
- [🔗 Aegis - MidstallSoftware](https://github.com/MidstallSoftware/aegis)
- [🔗 OpenSignal](https://github.com/asifali411/OpenSignal)
- [📝 Quake 2 on FPGA](https://blog.mikhe.ch/quake2-on-fpga/)
- [🔗 mVIDIA](https://jaso1024.com/mvidia/)
- [🎞️ RISC-V Single Cycle Core in Verilog](https://www.youtube.com/playlist?list=PL5AmAh9QoSK7Fwk9vOJu-3VqBng_HjGFc)
- [🎞️ SPI Project in FPGA - Ambient Light Sensor](https://youtube.com/playlist?list=PLnAoag7Ew-vq5kOyfyNN50xL718AtLoCQ)
- [🔗 FPGA Conway](https://github.com/AdaMahdavi/FPGA-Conway)
- [🔗 Verilaxi](https://github.com/nelsoncsc/verilaxi)
- [🔗 OpenTitan - open-source silicon root of trust (lowRISC)](https://github.com/lowRISC/opentitan)
- [🔗 PULP Platform - open-source RISC-V hardware](https://github.com/pulp-platform)
- [📝 ZipCPU Blog - FPGA, formal verification and CPU design](https://zipcpu.com/)
- [🔗 VexRiscv - FPGA-friendly RISC-V CPU](https://github.com/SpinalHDL/VexRiscv)
- [🔗 PicoRV32 - Size-optimized RISC-V CPU](https://github.com/YosysHQ/picorv32)
- [🔗 Verilog Ethernet - Ethernet MAC, UDP/IP and PCIe designs (Alex Forencich)](https://github.com/alexforencich/verilog-ethernet)

## Getting an FPGA Board

You can learn a lot with simulation alone, but programming a real board makes the concepts concrete. Pick a board whose toolchain you are comfortable with:

- [🔗👶 Digilent Basys 3 (AMD Artix-7)](https://digilent.com/reference/programmable-logic/basys-3/start) - Classic teaching board used by many university courses; uses the free AMD Vivado.
- [🔗👶 iCEBreaker (Lattice iCE40)](https://1bitsquared.com/products/icebreaker) - Fully supported by the open-source Yosys + nextpnr toolchain.
- [🔗👶 Sipeed Tang Nano 9K (Gowin)](https://wiki.sipeed.com/hardware/en/tang/Tang-Nano-9K/Nano-9K.html) - Very cheap board with HDMI output, supported by open-source tools.
- [🔗 Alchitry Boards](https://alchitry.com/) - Beginner-oriented boards with their own tutorials.
- [🔗👶 Access an FPGA right now!](https://ps1.fpgas.online/fpgas/) - No board? Use a remote one.

## Roadmap

The world of FPGA and ASIC engineering thrives on two crucial disciplines: **Implementation Engineering** and **Verification Engineering**. While intertwined, each plays a distinct role in bringing innovative ideas to life in programmable hardware or custom silicon. Engineers who target custom chips additionally need **ASIC-specific** physical design and sign-off skills.

**Implementation Engineers** are the architects of the design, meticulously crafting it by translating algorithms and functionalities into hardware configurations. They leverage their expertise in *hardware description languages* and *synthesis tools* to optimize design performance and resource utilization.

**Verification Engineers**, on the other hand, safeguard the design's integrity. They design and execute comprehensive *test strategies*, utilizing advanced *simulation tools* and real-world test setups. By comparing expected behavior with actual outputs, they identify and eliminate errors, ensuring the final product functions as intended.

Both disciplines are equally critical, working hand-in-hand throughout the development process. Implementation engineers rely on verification feedback to refine their designs, while verification engineers depend on accurate implementation models to create effective tests.

The topics are ordered roughly in the sequence in which you should learn them: **Common Skills** first (needed by everyone), then the **Implementation**, **Verification** and **ASIC Design** specializations, and finally domains, community and career. Each topic is tagged with its priority.

### ✳️ Common Skills

#### 🔵 Digital Logic and Computer Architecture

**Priority: Required**

Logic gates, combinational and sequential circuits, finite-state machines, memory architectures, and how CPUs and memory systems work. This can be extended to specialized architectures, such as Graphics Processing Units (GPUs) or custom accelerator designs.

- [🔗👶 Nand2Tetris - Build a Modern Computer from First Principles](https://www.nand2tetris.org/)
- [🔗💎 Computation Structures (MIT 6.004)](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2017/)
- [📘💎 Digital Design - Morris Mano, Michael Ciletti](https://a.co/d/c3tBaoc)
- [📘👶💎 Digital Design and Computer Architecture: ARM Edition -  Sarah Harris, David Harris](https://a.co/d/4otoVvI)
- [📘👶💎 Digital Design and Computer Architecture: RISC-V Edition -  Sarah Harris, David Harris](https://a.co/d/61l7Jtb)
- [🔗 Digital Design and Computer Architecture - Book Companion Site (slides, labs, errata)](https://pages.hmc.edu/harris/ddca/)
- [🎞️💎 Digital Design and Computer Architecture - Onur Mutlu, ETH Zürich (YouTube Channel)](https://www.youtube.com/@onurmutlulectures)
- [📘💎 Computer Organization and Design: ARM Edition -  David A. Patterson, John L. Hennessy](https://a.co/d/8YPUXG7)
- [📘👶 Digital Fundamentals - Thomas L. Floyd](https://a.co/d/2lgJKNX)
- [📝 Tiny Tapeout > Digital Design Guide](https://tinytapeout.com/digital_design/)
- [📝 FPGA Fundamentals - Nandland](https://nandland.com/fpga-101/)
- [🎞️👶 Build an 8-bit computer from scratch](https://eater.net/8bit/)
- [🔗 The RISC-V Instruction Set Specifications](https://riscv.org/technical/specifications/)
- [📝 Every GPU Architecture in a Staggering Visual Timeline](https://sheets.works/data-viz/every-gpu)
- [🔗 IC Design Tips](https://www.icdesigntips.com/)

#### 🔵 Linux, Scripting and Version Control

**Priority: Required**

FPGA and ASIC tools run mostly on Linux and are driven by scripts. Comfort with the command line, Git, and a scripting language (Tcl, Python, Make, shell) lets you automate builds, simulations and regressions, and is expected in every job.

- [🔗👶💎 The Missing Semester of Your CS Education (MIT)](https://missing.csail.mit.edu/)
- [🎞️ Git Tutorial for Beginners: Learn Git in 1 Hour](https://www.youtube.com/watch?v=8JJ101D3knE)
- [🎞️ Git for Professionals Tutorial - Tools & Concepts for Mastering Version Control with Git](https://www.youtube.com/watch?v=Uszj_k0DGsg)
- [📘👶💎 Pro Git - Scott Chacon, Ben Straub](https://git-scm.com/book/en/v2)
- [🔗 Apache® Subversion®](https://subversion.apache.org/)
- [📝 Why you need to learn Tcl](https://vhdlwhiz.com/why-you-need-to-learn-tcl/)
- [📝 Top 10 Tips for efficient Perl Scripting for Chip Designers](https://www.design-reuse.com/articles/20613/perl-scripting-chip-design.html)
- [🔗 Edalize - Python library for driving FPGA and simulator tools](https://github.com/olofk/edalize)
- [🔗 FuseSoC - Package manager and build abstraction tool for FPGA/ASIC IP cores](https://github.com/olofk/fusesoc)
- [🔗 HDL Containers - Ready-to-use container images of open-source EDA tools (for CI)](https://github.com/hdl/containers)

#### 🔵 Hardware Description Languages (HDLs)

**Priority: Required**

Knowledge of VHDL and/or Verilog is crucial as they're commonly used to design and describe digital circuits. Pick one first and learn the other later; the concepts transfer.

- [📝 VHDLwhiz - Basic VHDL Tutorials](https://vhdlwhiz.com/basic-vhdl-tutorials/)
- [🎞️ VHDLwhiz.com (YouTube Channel)](https://www.youtube.com/@VHDLwhiz)
- [📝👶💎 HDLBits — Verilog Practice](https://hdlbits.01xz.net/wiki/Main_Page)
- [📝 FPGA designs with Verilog](https://verilogguide.readthedocs.io/en/latest/index.html)
- [📝👶 Learn Verilog - Nandland](https://nandland.com/learn-verilog/)
- [📝👶 Learn VHDL - Nandland](https://nandland.com/learn-vhdl/)
- [📘👶 Free Range VHDL - Bryan Mealy, Fabrizio Tappero](https://github.com/fabriziotappero/Free-Range-VHDL-book)
- [📝 SystemVerilog Tutorial - ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-tutorial)
- [🔗 Doulos - SystemVerilog Knowhow](https://www.doulos.com/knowhow/systemverilog/)

Modern HDLs and HDL-embedded generators (optional, learn them after you are comfortable with Verilog or VHDL):

- [🔗 Veryl](https://github.com/veryl-lang/veryl)
- [📝 Chisel - Hardware construction language embedded in Scala](https://www.chisel-lang.org/)
- [📝 SpinalHDL - Scala-based HDL](https://spinalhdl.github.io/SpinalDoc-RTD/master/index.html)
- [📝 Amaranth HDL - Python-based HDL](https://amaranth-lang.org/docs/amaranth/latest/)
- [🔗 LiteX - Build your own FPGA-based SoC in Python](https://github.com/enjoy-digital/litex)

#### 🔵 RTL Design Practices

**Priority: Required**

Writing code that synthesizes into the hardware you intend: registers versus latches, blocking versus non-blocking assignments, finite-state machine (FSM) coding styles, pipelining, and number representation and arithmetic (fixed-point, multipliers, CORDIC). Bad habits here cause bugs that are hard to find later.

- [📝👶 Verilog Blocking and Non-Blocking Statements - ChipVerify](https://www.chipverify.com/verilog/verilog-blocking-non-blocking-statements)
- [📝💎 Nonblocking Assignments in Verilog Synthesis, Coding Styles That Kill! - Clifford E. Cummings](http://www.sunburst-design.com/papers/CummingsSNUG2000SJ_NBA.pdf)
- [📝👶 Verilog Finite State Machine - ChipVerify](https://www.chipverify.com/verilog/verilog-finite-state-machine)
- [📝 Verilog Coding Style Guide - lowRISC](https://github.com/lowRISC/style-guides/blob/master/VerilogCodingStyle.md)
- [📝👶 Fixed Point Numbers in Verilog - Project F](https://projectf.io/posts/fixed-point-numbers-in-verilog/)
- [📝 CORDIC - ZipCPU](https://zipcpu.com/dsp/2017/08/30/cordic.html)
- [📝 Strategies for Pipelining - ZipCPU](https://zipcpu.com/blog/2017/08/14/strategies-for-pipelining.html)

Pipeline design and flow control (skid buffers, FIFOs): decoupling stages, managing backpressure, and avoiding timing bottlenecks in pipelined designs.

- [📝 Skid Buffer (ZipCPU)](https://zipcpu.com/blog/2019/05/22/skidbuffer.html)
- [📝 Pipeline Skid Buffer (FPGA CPU)](https://fpgacpu.ca/fpga/Pipeline_Skid_Buffer.html)
- [📝 Designing Skid Buffers for Pipelines (Chipmunk Logic)](https://chipmunklogic.com/digital-logic-design/designing-skid-buffers-for-pipelines/)
- [📝 A Case Study on Effective Pipeline Design in Digital System](https://verilog-meetup.com/2024/06/20/a-case-study-on-effective-pipeline-design-in-digital-system/)

#### 🔵 Simulation, Testbenches and Debugging

**Priority: Required**

Every designer simulates their own code. Learn to write simple self-checking testbenches, read waveforms, lint your code, and debug on real hardware with logic analyzers built into the FPGA. (Advanced verification methodology is covered under Verification Engineer.)

- [📝👶 SystemVerilog TestBench](https://www.chipverify.com/systemverilog/systemverilog-simple-testbench)
- [🔗 EDA Playground - Run simulations in the browser](https://www.edaplayground.com/)
- [🔗 cocotb - Python-based testbenches for VHDL and Verilog](https://docs.cocotb.org/en/stable/)
- [🔗 WaveDrom](https://wavedrom.com/)
- [🔗 DigitalJS](https://digitaljs.tilk.eu/#)
- [🔗 Monosketch](https://monosketch.io/)
- [📝 Debugging with Speed and Precision: Mastering the Art of FPGA Debugging](https://fpgainsights.com/fpga/debugging-with-speed-and-precision-mastering-the-art-of-fpga-debugging/)
- [📝 Vivado Design Suite User Guide: Programming and Debugging (UG908) - ILA and VIO debug cores](https://docs.amd.com/r/en-US/ug908-vivado-programming-debugging)
- [🔗 Verible - SystemVerilog parser, linter and formatter](https://github.com/chipsalliance/verible)

#### 🔵 FPGA Architecture

**Priority: Required**

What is inside an FPGA: look-up tables (LUTs), flip-flops, carry chains, block RAM, DSP slices, clocking resources (PLL/MMCM), I/O standards and routing. Knowing the architecture explains why some code maps well to hardware and some does not.

- [📝👶 Field-programmable gate array - Wikipedia](https://en.wikipedia.org/wiki/Field-programmable_gate_array)
- [📝 7 Series FPGAs Configurable Logic Block User Guide (UG474)](https://docs.amd.com/v/u/en-US/ug474_7Series_CLB)
- [📝 7 Series FPGAs Memory Resources User Guide (UG473)](https://docs.amd.com/v/u/en-US/ug473_7Series_Memory_Resources)
- [📝 7 Series FPGAs Clocking Resources User Guide (UG472)](https://docs.amd.com/v/u/en-US/ug472_7Series_Clocking)
- [📝 7 Series DSP48E1 Slice User Guide (UG479)](https://docs.amd.com/v/u/en-US/ug479_7Series_DSP48E1)

#### 🔵 FPGA Toolchain

**Priority: Required**

Understanding of specific FPGA toolchains like Xilinx Vivado, Intel Quartus, etc. Vendor tools have free editions for most small and mid-size devices; open-source tools are a great way to understand what each step of the flow does.

**Simulation, synthesis and place-and-route (open source):**

- [🔗👶💎 OSS CAD Suite - Ready-to-use binary builds of Yosys, nextpnr, Verilator, Icarus Verilog, SymbiYosys and more](https://github.com/YosysHQ/oss-cad-suite-build)
- [🔗 Yosys Open SYnthesis Suite](https://github.com/YosysHQ/yosys)
- [📝 Yosys Documentation](https://yosyshq.readthedocs.io/projects/yosys/en/latest/)
- [🔗 nextpnr](https://github.com/YosysHQ/nextpnr)
- [🔗 Icarus Verilog - Verilog simulator](https://github.com/steveicarus/iverilog)
- [🔗 Verilator - Fast SystemVerilog simulator and linter](https://verilator.org/guide/latest/)
- [🔗 GHDL - an open-source simulator for the VHDL language](https://github.com/ghdl/ghdl)
- [🔗 GTKWave - a fully featured GTK+ based wave viewer](https://github.com/gtkwave/gtkwave)
- [🔗 openFPGALoader - Universal utility for programming FPGAs](https://github.com/trabucayre/openFPGALoader)
- [🔗 apio - Open-source ecosystem for FPGA boards](https://github.com/FPGAwars/apio)
- [🔗 F4PGA - Open-source FPGA toolchain project](https://f4pga.org/)

**Vendor and commercial tools:**

- [🔗 AMD (Xilinx) Design Tools](https://www.xilinx.com/products/design-tools.html)
- [🔗 Intel (Altera) Development Tools](https://www.intel.com/content/www/us/en/products/details/fpga/development-tools.html)
- [🔗 Lattice FPGA Design Software](https://www.latticesemi.com/Products/DesignSoftwareAndIP)
- [🔗 Gowin EDA](https://www.gowinsemi.com/en/support/download_eda/)
- [🔗 ModelSim HDL simulator](https://www.intel.com/content/www/us/en/software-kit/750666/modelsim-intel-fpgas-standard-edition-software-version-20-1-1.html)
- [🔗 Cadence Design Tools](https://www.cadence.com/en_US/home/tools.html)
- [🔗 Synopsys Design Tools](https://www.synopsys.com/implementation-and-signoff.html)

#### 🔵 Familiarity with FPGA and ASIC Design Flow

**Priority: Required**

Understanding the overall process of design, from specification to synthesis and place-and-route, is helpful in order to interface effectively with the design team.

- [📘 A Hands-On Guide to Designing Embedded Systems - Adam Taylor, Dan Binnun, Saket Srivastava](https://www.amazon.com/Hands-Guide-Designing-Embedded-Systems/dp/1630816833)
- [📝 Understanding FPGA Programming and Design Flow](https://hardwarebee.com/understanding-fpga-programming-and-design-flow/)
- [📝 ASIC Design Flow in VLSI Engineering Services – A Quick Guide](https://www.einfochips.com/blog/asic-design-flow-in-vlsi-engineering-services-a-quick-guide/)
- [📝 Vivado Design Suite User Guide: Design Flows Overview (UG892)](https://docs.amd.com/r/en-US/ug892-vivado-design-flows-overview)

#### 🔵 Timing Analysis and Constraints

**Priority: Required**

A design only works if signals arrive on time. Learn setup and hold times, clock frequency and slack, critical paths, and how to write timing constraints (SDC/XDC) and read timing reports. Proficiency in these is what makes a design run at the intended clock speed.

- [📝💎 Vivado Design Suite User Guide: Using Constraints (UG903)](https://docs.amd.com/r/en-US/ug903-vivado-using-constraints)
- [📝 Vivado Design Analysis and Closure Techniques (UG906)](https://docs.amd.com/r/en-US/ug906-vivado-design-analysis)
- [🔗 OpenSTA - Open-source static timing analyzer](https://github.com/The-OpenROAD-Project/OpenSTA)

#### 🔵 Clock Domain Crossing and Resets

**Priority: Required**

Signals that cross between unrelated clocks, and resets that are not handled properly, are among the most common causes of intermittent hardware bugs. Learn synchronizers, handshakes, asynchronous FIFOs and reset strategies.

- [📝💎 Clock Domain Crossing (CDC) Design & Verification Techniques Using SystemVerilog - Clifford E. Cummings](http://www.sunburst-design.com/papers/CummingsSNUG2008Boston_CDC.pdf)
- [📝💎 Simulation and Synthesis Techniques for Asynchronous FIFO Design - Clifford E. Cummings](http://www.sunburst-design.com/papers/CummingsSNUG2002SJ_FIFO1.pdf)
- [📝 Asynchronous & Synchronous Reset Design Techniques - Part Deux - Clifford E. Cummings](http://www.sunburst-design.com/papers/CummingsSNUG2003Boston_Resets.pdf)
- [📝 Clock Domain Crossing - ZipCPU](https://zipcpu.com/blog/2017/10/20/cdc.html)
- [🔗 More papers on synthesis, resets and CDC - Sunburst Design](http://www.sunburst-design.com/papers/)

#### 🔵 Interfaces, Protocols and Memory

**Priority: Required**

Real designs talk to other chips and blocks. Start with simple serial protocols (UART, SPI), then learn on-chip bus standards (AXI, AXI-Stream, Wishbone), and later memory (DDR) and high-speed interfaces (Ethernet, PCIe). Both implementation and verification engineers need to be aware of requirements, architecture, and interconnect standards and interfaces.

- [📝👶 RS-232 (UART) Serial Interface - FPGA4fun](https://www.fpga4fun.com/SerialInterface.html)
- [📝👶 SPI - FPGA4fun](https://www.fpga4fun.com/SPI.html)
- [📝 Building a Simple AXI-Lite Slave - ZipCPU](https://zipcpu.com/blog/2020/03/08/easyaxil.html)
- [📝 Designing a Custom AXI Slave (Avnet PDF)](https://www.avnet.com/wcm/connect/557e3453-20d7-4737-b2a8-8afc404dc81e/designing_a_custom_axi_slave_rev1.pdf?MOD=AJPERES&ContentCache=NONE&CACHE=NONE&CVID=picU33N)
- [🔗 AMBA AXI Protocol Specification - Arm](https://developer.arm.com/documentation/ihi0022/)
- [🔗 Wishbone B3 Specification](https://wishbone-interconnect.readthedocs.io/)
- [🔗 LiteDRAM - Small footprint and configurable DRAM core](https://github.com/enjoy-digital/litedram)
- [🔗 Verilog Ethernet (Alex Forencich)](https://github.com/alexforencich/verilog-ethernet)
- [🔗 Verilog PCI Express Components (Alex Forencich)](https://github.com/alexforencich/verilog-pcie)

#### 🔵 Industry Standards

**Priority: Recommended**

Familiarity with relevant industry standards can be important, especially in fields like telecommunications or automotive.

- [🔗 IEEE 1800 - SystemVerilog (free via IEEE Get Program)](https://ieeexplore.ieee.org/document/10458102)
- [🔗 The RISC-V Instruction Set Specifications](https://riscv.org/technical/specifications/)
- [🔗 Accellera Standards (UVM, IP-XACT and more)](https://www.accellera.org/downloads/standards)

----------------

### ✳️ Implementation Engineer

As an FPGA (Field Programmable Gate Array) implementation engineer, there are several important topics to be well-versed in:

#### 🔵 FPGA Design Methodologies

**Priority: Required**

Understanding of various FPGA design techniques and best practices is important.

FPGA design methodologies encompass a broad range of techniques and strategies used in the process of designing and implementing digital logic on FPGA devices. Here are some key methods:

##### 🔶 RTL Design

Register Transfer Level (RTL) design is a method where the digital system is described at a high level in terms of data flow between registers and the logical operations performed on the data. This allows the designer to focus on the logic functionality and data flow, rather than the specifics of how each gate is connected.

- [📝 Understanding RTL Design: Building the Foundation of Digital Systems](https://www.linkedin.com/pulse/understanding-rtl-design-building-foundation-digital-systems-pandey/)

##### 🔶 High-Level Synthesis (HLS)

HLS is a design methodology where the digital system is described in a high-level programming language such as C or C++, and then automatically converted into RTL code by an HLS tool. This approach can be faster and easier than writing RTL code directly, especially for complex algorithms. It is an advanced topic; learn RTL first.

- [📘 High-Level Synthesis Made Easy: Synthesizing Behavioral Descriptions directly into Hardware Circuits](https://www.hlsbook.com/)
- [📘 High-Level Synthesis Blue Book](https://hlsbluebook.org/)
- [🔗 Vitis HLS — Vitis™ Tutorials](https://xilinx.github.io/Vitis-Tutorials/2021-1/build/html/docs/Getting_Started/Vitis_HLS/Getting_Started_Vitis_HLS.html)

##### 🔶 IP Core Based Design

IP (Intellectual Property) cores are pre-designed circuit blocks that can be reused in multiple designs. Using IP cores can significantly speed up the design process and improve the reliability of the design, since the IP cores have been pre-verified.

- [📝 Basics of core-based FPGA design](https://www.embedded.com/basics-of-core-based-fpga-design-part-1-core-types-trade-offs/)
- [📝 IP Cores For FPGA Designs](https://www.electronicsforu.com/electronics-projects/electronics-design-guides/ip-cores-fpga-designs)
- [📝 So you want to Design a FPGA IP Core!](https://www.hackster.io/adam-taylor/so-you-want-to-design-a-fpga-ip-core-56e0f1)

##### 🔶 Hardware-Software Co-Design

In many FPGA applications, a portion of the system functionality is implemented in software running on an embedded processor, while other portions are implemented in custom hardware on the FPGA. Hardware-software co-design involves designing the hardware and software components together to achieve the best overall system performance.

- [📝 Hardware/Software Co-Design: The Five Core Principles](https://www.electronicdesign.com/technologies/eda/article/21267771/recogni-hardwaresoftware-codesign-the-five-core-principles)

##### 🔶 Timing-Driven Design

This design methodology prioritizes meeting timing constraints. This may involve strategies such as pipelining to increase clock speed, carefully partitioning the design to reduce routing congestion, or using timing constraints files to guide the place-and-route process.

- [📝💎 Vivado Design Suite User Guide: Design Methodology Guide (UG949)](https://docs.amd.com/r/en-US/ug949-vivado-design-methodology)

##### 🔶 Resource-Optimized Design

This involves making the most efficient use of FPGA resources such as logic blocks, DSP blocks, and memory blocks. It might involve strategies such as sharing resources between multiple functions, or optimizing the logic to reduce the number of logic blocks used.

- [📝💎 Vivado Design Suite User Guide: Synthesis (UG901) - HDL coding styles that infer RAMs, DSPs and shift registers](https://docs.amd.com/r/en-US/ug901-vivado-synthesis)

These methodologies are not mutually exclusive and can often be used together in the same design. The appropriate methodology to use depends on the specific design goals and constraints.

#### 🔵 SoC FPGAs and Soft Processors

**Priority: Recommended**

Many modern FPGAs combine programmable logic with hard processor cores (for example AMD Zynq), or run a processor you build in the fabric (soft cores such as MicroBlaze or RISC-V). Working at this boundary needs both hardware and embedded software knowledge: bus interfaces, device drivers, booting and Linux.

- [📘👶 The Zynq Book](http://www.zynqbook.com/)
- [🔗 PYNQ - Python productivity for AMD adaptive computing platforms](http://www.pynq.io/)
- [🔗 LiteX - Build your own FPGA-based SoC in Python](https://github.com/enjoy-digital/litex)
- [🔗 VexRiscv - FPGA-friendly RISC-V CPU](https://github.com/SpinalHDL/VexRiscv)
- [🔗 PicoRV32 - Size-optimized RISC-V CPU](https://github.com/YosysHQ/picorv32)

#### 🔵 Digital Signal Processing

**Priority: Recommended**

Depending on the application, an understanding of digital signal processing concepts can be very useful.

- [📘💎 The Scientist and Engineer's Guide to Digital Signal Processing - Steven W. Smith](https://www.dspguide.com/pdfbook.htm)
- [🔗 controlpaths - Blogs in control and signal processing](https://www.controlpaths.com/)
- [🎞️ Digital Signal Processing (ECSE-4530) Lectures, Fall 2014 (YouTube Playlist)](https://youtube.com/playlist?list=PLuh62Q4Sv7BUSzx5Jr8Wrxxn-U10qG1et)
- [📘 Real-Time Digital Signal Processing: Fundamentals, Implementations and Applications - Sen M. Kuo, Bob H. Lee, Wenshun Tian](https://www.wiley.com/en-us/Real+Time+Digital+Signal+Processing%3A+Fundamentals%2C+Implementations+and+Applications%2C+3rd+Edition-p-9781118414323)
- [📘 Schaum's Outline of Signals and Systems - Hwei P. Hsu](https://www.mhprofessional.com/schaum-s-outline-of-signals-and-systems-fourth-edition-9781260454246-usa)
- [📘💎 Digital Signal Processing - John G. Proakis, Dimitris K. Manolakis](https://a.co/d/75P5PiE)
- [🎞️ Discrete Fourier Transform - Simple Step by Step](https://www.youtube.com/watch?v=mkGsMWi_j4Q)
- [🎞️ The Fast Fourier Transform (FFT): Most Ingenious Algorithm Ever?](https://youtu.be/h7apO7q16V0)
- [🎞️ The FFT Algorithm - Simple Step by Step](https://www.youtube.com/watch?v=htCj9exbGo0)

#### 🔵 Power and Thermal Management

**Priority: Optional**

Techniques to optimize the power consumption and manage heat dissipation.

- [📝 Vivado Design Suite User Guide: Power Analysis and Optimization (UG907)](https://docs.amd.com/r/en-US/ug907-vivado-power-analysis-optimization)

#### 🔵 Board Bring-up and PCB Design for FPGAs

**Priority: Optional**

When a design moves from a development board to custom hardware, you need to understand FPGA configuration and boot, power supplies and sequencing, pin assignment, and signal integrity for high-speed signals.

- [📝 7 Series FPGAs Configuration User Guide (UG470)](https://docs.amd.com/v/u/en-US/ug470_7Series_Config)
- [📝 UltraScale Architecture PCB Design User Guide (UG583)](https://docs.amd.com/r/en-US/ug583-ultrascale-pcb-design)

#### 🔵 Software Development Skills

**Priority: Recommended**

Including proficiency in languages such as C/C++, Python, and knowing how to work with software drivers for hardware interfaces.

- [📘 The Little Book of C](https://little-book-of.github.io/c/books/en-US/book.html)

#### 🔵 Embedded Systems

**Priority: Optional**

Understanding of embedded system design, including both hardware and software aspects.

- [🔗 Embedded Systems Engineering Roadmap](https://github.com/m3y54m/Embedded-Engineering-Roadmap)

#### 🔵 Application Domains

**Priority: Optional**

FPGAs are used in networking, video and imaging, software-defined radio, motor control, finance, hardware security, and machine-learning acceleration. Pick a domain that interests you and build a project in it.

- [🔗 hls4ml - Machine learning inference on FPGAs](https://fastmachinelearning.org/hls4ml/)
- [🎞️ Coursera - Hardware Security](https://www.coursera.org/learn/hardware-security)
- [🔗 Verilog Ethernet (Alex Forencich)](https://github.com/alexforencich/verilog-ethernet)

----------------

### ✳️ Verification Engineer

The other side of the coin is the verification engineer, who plays a crucial role in the development of hardware and software systems by ensuring the design meets the specified requirements. Verification is a large part of both FPGA and ASIC projects, and in ASIC work it usually takes more effort than design itself. Here are several important subjects and topics that a Verification Engineer should know:

#### 🔵 Hardware Verification Languages (HVLs)

**Priority: Required**

These include SystemVerilog, which is commonly used for hardware verification, and others like Property Specification Language (PSL).

- [📝 SystemVerilog Tutorial](https://www.asic-world.com/systemverilog/tutorial.html)
- [📝 SystemVerilog Tutorial - ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-tutorial)
- [📝 SystemVerilog.io](https://www.systemverilog.io/)
- [📝 Sv-lang](https://sv-lang.com/index.html)
- [📝 VLSI Verify](https://vlsiverify.com/)
- [📝 Property Specification Language Tutorial](https://www.project-veripage.com/psl_tutorial_1.php)

#### 🔵 Testbench Creation

**Priority: Required**

Verification engineers must know how to develop testbenches to simulate and verify the functionality and performance of a design, including self-checking testbenches, reference models and scoreboards.

- [🔗 cocotb - Python-based testbenches for VHDL and Verilog](https://docs.cocotb.org/en/stable/)
- [🔗 VUnit - Unit testing framework for VHDL/SystemVerilog](https://vunit.github.io/)
- [🔗 OSVVM - Open Source VHDL Verification Methodology](https://osvvm.org/)
- [🔗 UVVM - Universal VHDL Verification Methodology](https://uvvm.org/)
- [🔗💎 Verification Academy - Courses, cookbooks and forums](https://verificationacademy.com/)
- [📝 The Python for Verification Series](https://verificationacademy.com/news/the-python-for-verification-series)
- [🔗 cocotb, a coroutine based cosimulation library for writing VHDL and Verilog testbenches in Python](https://www.cocotb.org)

#### 🔵 Randomization, Assertions and Functional Coverage

**Priority: Required**

Constrained-random stimulus finds corner cases that hand-written tests miss. Assertions and functional coverage are key for ensuring the design behaves as expected under all conditions, and for making sure all important scenarios are tested.

- [📝 SystemVerilog Randomization - ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-randomization)
- [📝 SystemVerilog Assertions - ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-assertions)
- [📝 SystemVerilog Functional Coverage - ChipVerify](https://www.chipverify.com/systemverilog/systemverilog-functional-coverage)
- [🔗 Coverage Cookbook - Verification Academy](https://verificationacademy.com/cookbook/coverage)
- [🔗 cocotb-coverage - Functional coverage and constrained randomization for cocotb](https://github.com/mciepluc/cocotb-coverage)
- [📘💎 SystemVerilog for Verification - Chris Spear , Greg Tumbush](https://link.springer.com/book/10.1007/978-1-4614-0715-7)

#### 🔵 Universal Verification Methodology (UVM)

**Priority: Recommended**

This is an industry-standard methodology for verification of hardware designs, and is expected in most ASIC verification jobs.

- [🔗 UVM (Standard Universal Verification Methodology)](https://www.accellera.org/downloads/standards/uvm)
- [📝 UVM 1.2 User Guide](http://www.accellera.org/images//downloads/standards/uvm/uvm_users_guide_1.2.pdf)
- [📝👶 UVM Guide for Beginners](https://colorlesscube.com/uvm-guide-for-beginners/)
- [📝👶 Easier UVM - Doulos](https://www.doulos.com/knowhow/systemverilog/uvm/easier-uvm/)
- [🔗 UVM Cookbook - Verification Academy](https://verificationacademy.com/cookbook/uvm-universal-verification-methodology)
- [🔗 pyuvm - Python implementation of UVM on top of cocotb](https://github.com/pyuvm/pyuvm)
- [📘 The UVM Primer: A Step-by-Step Introduction to the Universal Verification Methodology - Ray Salemi](https://www.amazon.com/dp/0974164933?_encoding=UTF8&psc=1&ref_=cm_sw_r_cp_ud_dp_SFYBP2WRG9PGJYY6RBEE)

#### 🔵 Formal Verification Methods

**Priority: Recommended**

Including equivalence checking and model checking.

- [📝👶💎 Verilog, Formal Verification and Verilator Beginner's Tutorial](https://zipcpu.com/tutorial/)
- [📝 SymbiYosys - Open-source formal verification flow](https://yosyshq.readthedocs.io/projects/sby/en/latest/)
- [📝 11 Myths About Formal Verification](https://www.electronicdesign.com/technologies/eda/article/21807132/11-myths-about-formal-verification)
- [📝 Verilator Direct Programming Interface](https://verilator.org/guide/latest/connecting.html#direct-programming-interface-dpi)

----------------

### ✳️ ASIC Design Engineer

ASIC (Application-Specific Integrated Circuit) engineers take RTL through synthesis, floorplanning, placement, clock tree synthesis, routing and sign-off to produce the final chip layout (GDSII). Since a chip cannot be patched after fabrication, verification, timing sign-off and physical checks are even more critical than in FPGA design. Open-source tools and open process design kits (PDKs) now let anyone learn this flow for free. The front-end work (RTL, verification, synthesis, DFT) builds directly on the Common Skills and Verification sections above; the back-end work is physical design.

#### 🔵 RTL-to-GDSII Flow

**Priority: Required**

The complete path from RTL to a manufacturable layout, using free tools. Tiny Tapeout and the Zero to ASIC Course are the easiest way to run this flow end to end.

- [🔗👶💎 Zero to ASIC Course](https://www.zerotoasiccourse.com/)
- [🔗👶💎 Tiny Tapeout: from idea to chip design in minutes!](https://tinytapeout.com/)
- [📝💎 LibreLane - Open-source ASIC implementation flow](https://librelane.readthedocs.io)
- [🔗 OpenROAD Project](https://theopenroadproject.org/)
- [📝 OpenROAD Documentation](https://openroad.readthedocs.io/)
- [🔗 OpenROAD-flow-scripts](https://github.com/The-OpenROAD-Project/OpenROAD-flow-scripts)
- [🔗 Yosys Open SYnthesis Suite](https://github.com/YosysHQ/yosys)

#### 🔵 Design for Test (DFT)

**Priority: Recommended**

Testability features are added to the hardware design to make it easier to test and debug manufactured chips. This includes scan chains, automatic test pattern generation (ATPG) and built-in self-test (BIST). Unlike FPGAs, every manufactured ASIC must be tested, so DFT is a core ASIC skill.

- [📝 DESIGN FOR TEST](https://www.faststreamtech.com/services/semiconductor-design/design-for-test/)
- [🔗 Fault - Open-source EDA tool for DFT (scan insertion and ATPG)](https://github.com/Cloud-V/Fault)

#### 🔵 Low-Power Design

**Priority: Recommended**

Techniques such as clock gating, power gating and multiple voltage domains, described with the Unified Power Format (UPF). Power is usually a key constraint in chip projects. Learn the basics from the commercial tool documentation and training of [Cadence](https://www.cadence.com/en_US/home/tools.html) and [Synopsys](https://www.synopsys.com/implementation-and-signoff.html).

#### 🔵 Open Process Design Kits (PDKs)

**Priority: Recommended**

A PDK describes a foundry's manufacturing process (cell libraries, design rules, device models). Open PDKs are what make open-source chip design possible.

- [🔗 SkyWater SKY130 PDK](https://github.com/google/skywater-pdk)
- [📝 SkyWater SKY130 PDK Documentation](https://skywater-pdk.readthedocs.io/)
- [🔗 GlobalFoundries GF180MCU PDK](https://github.com/google/gf180mcu-pdk)
- [🔗 IHP Open PDK (SG13G2 SiGe BiCMOS)](https://github.com/IHP-GmbH/IHP-Open-PDK)

#### 🔵 Layout, Physical Verification and Sign-off

**Priority: Recommended**

Viewing and editing layouts, checking design rules (DRC) and layout-versus-schematic (LVS), and verifying timing before tape-out.

- [🔗 KLayout - Layout viewer and editor](https://www.klayout.de/)
- [🔗 Magic VLSI Layout Tool](http://opencircuitdesign.com/magic/)
- [🔗 Netgen - LVS and netlist comparison tool](http://opencircuitdesign.com/netgen/)
- [🔗 OpenSTA - Open-source static timing analyzer](https://github.com/The-OpenROAD-Project/OpenSTA)

#### 🔵 CMOS VLSI Fundamentals

**Priority: Recommended**

How transistors form gates and how gate-level behavior, delay and power follow from the circuit level.

- [📘💎 CMOS VLSI Design: A Circuits and Systems Perspective - Neil Weste, David Harris](https://pages.hmc.edu/harris/cmosvlsi/4e/index.html)
- [🎞️ Coursera - VLSI CAD Part I: Logic](https://www.coursera.org/learn/vlsi-cad-logic)
- [🎞️ YouTube Playlist - CMOS Digital VLSI Design](https://www.youtube.com/playlist?list=PLLy_2iUCG87Bdulp9brz9AcvW_TnFCUmM)

#### 🔵 Analog and Mixed-Signal Basics

**Priority: Optional**

Even digital ASICs contain analog blocks (PLLs, ADCs, I/O). Digital engineers benefit from knowing circuit simulation and schematic capture to understand what these blocks need from the digital side.

- [🔗 ngspice - Open-source circuit simulator](https://ngspice.sourceforge.io/)
- [🔗 Xschem - Schematic capture program](https://xschem.sourceforge.io/stefan/index.html)

#### 🔵 Prototyping and Tape-out

**Priority: Optional**

Large ASICs are usually prototyped on FPGAs before fabrication. Tape-out is the hand-off of the final layout to the foundry; low-cost shuttle services let students and hobbyists get real chips made.

- [🔗 Tiny Tapeout: from idea to chip design in minutes!](https://tinytapeout.com/)
- [🔗 wafer.space - Open-source silicon shuttle runs](https://wafer.space/)

## Community and Career

Hardware design is easier with other people to ask. Search before asking, share your code and the exact error message, and be specific about what you tried:

- [🔗 r/FPGA](https://www.reddit.com/r/FPGA/)
- [🔗 r/chipdesign](https://www.reddit.com/r/chipdesign/)
- [🔗 EEVblog Forum - FPGA](https://www.eevblog.com/forum/fpga/)
- [🔗 Electronics Stack Exchange - fpga tag](https://electronics.stackexchange.com/questions/tagged/fpga)
- [🔗 Verification Academy Forums](https://verificationacademy.com/forums)
- [🔗 Awesome HDL - Curated list of hardware design resources](https://github.com/hdl/awesome)

Typical entry-level roles are RTL/FPGA design engineer, design verification (DV) engineer, and physical design engineer. A public portfolio (simulated and hardware-tested projects on GitHub, ideally with testbenches and a README explaining the design) is the best way to show your skills, and interview preparation usually focuses on digital logic, FSMs, timing and clock domain crossing, and HDL coding questions:

- [📝 Verilog Interview Questions - VLSI Verify](https://vlsiverify.com/verilog/verilog-interview-questions/)
- [📝 HDLBits — Verilog Practice](https://hdlbits.01xz.net/wiki/Main_Page)

## Contribution

If you are an experienced FPGA or ASIC engineer, or a learner who found something that really helped, your input is welcome. In particular:

- **Which topics are missing or misplaced** in this roadmap?
- **What are the best resources you know** for each topic?

Please [open an issue](https://github.com/m3y54m/FPGA-ASIC-Roadmap/issues) or [make a pull request](https://github.com/m3y54m/FPGA-ASIC-Roadmap/pulls) with your suggestions, and read the [contribution guidelines](CONTRIBUTING.md) before adding resources.

## Acknowledgement

This roadmap started as [a discussion on Reddit](https://www.reddit.com/r/FPGA/comments/15g64oj/fpga_asic_design_roadmap/?utm_source=share&utm_medium=web2x&context=3) to gather information, categorize it under different topics, and decide how important each one is. Special thanks to [u/No_Delivery_1049](https://www.reddit.com/user/No_Delivery_1049/), whose [comment](https://www.reddit.com/r/FPGA/comments/15g64oj/comment/juir34n/?utm_source=share&utm_medium=web2x&context=3) served as the base of this roadmap, and to everyone who has contributed since.
