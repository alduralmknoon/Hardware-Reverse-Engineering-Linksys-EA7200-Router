# Hardware-Reverse-Engineering-Linksys-EA7200-Router
**Objectives**

To understand:
- Internal components and their functions
- Components interactions  
- Sketch PCB schematic Design
- Estimate Hardware Cost
- Obtain Firmware
- Reverse Engineer Firmware


We will be exploring and attempting to reverse engineer a router by Linksys, model number EA7200. After getting familiar with the PCB and internal components, our end goal is to dump the flash memory the router is using.

There are many ways to access the flash memory:
1. **Using debugging ports like JTAG and UART:** This method is the safest as it minimizes the risk of damaging the chips. However, it requires a good understanding of the hardware layout and datasheets.
2. **Physically extracting the flash memory and attaching it to a flash decoder:** This method involves directly interacting with the flash memory chip, but it has a higher risk of damaging the motherboard.
3. **Obtaining the encrypted firmware from the manufacturer and decrypting it:** This method involves working with the manufacturer's firmware, which may require advanced knowledge of encryption and decryption techniques.

_For Educational Purposes Only_
