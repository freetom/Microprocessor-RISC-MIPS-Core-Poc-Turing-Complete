# Microprocessor-RISC-MIPS-Core-Poc-Turing-Complete
Circuit of a microprocessor core with just the essential components that make it a turing complete machine

The System is of RISC architecture and implement partially the MIPS assembly language to have all the needed instruction to do any computation.<br />

The content is the core (ALU+Control Unit+Register File+...) of the microprocessor without Pipeline, MMU, TLB, Cache, Bus of any kind (a pre-existing integrated circuit for RAM has been used as memory), Program status word, Interrupts (internal/external), other modern cool stuff like ACPI etc...

Is just a very very basic core.

A test program is loaded (in binary form) in the ROM when you open up the project. It computes the factorial number of a given number.


For further information, there's the project file, the program file and a subset of the MIPS instruction set.


The circuit has been developed with Logic Circuit http://www.logiccircuit.org/


Tomas Bortoli - 2013
