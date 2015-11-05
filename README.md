# libmc1322x-interrupt-dissection
This repository is for educational purposes only. It does not compile. Purpose is to understand the interrupt mechanism of the mc1322x (hardware) / libmc1322x (software). Read comments in source code if interested. 

#start.S

This file contains the interrupt vector table. 

# Fetch

Professor Chen mentioned this paragraph will be important: 

"The "fetch" method loads the PC indirectly, using the address of some entry inside the interrupt vector table to pull an address out of that table, and then loading the PC with that address.[5] Each and every entry of the IVT is the address of an interrupt service routine. All Motorola/Freescale microcontrollers use the fetch method." (taken from https://en.wikipedia.org/wiki/Interrupt_vector_table). 

# Findings
None yet
