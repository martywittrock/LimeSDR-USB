### Making Enclosure
current status:
 
- 1st batch for enclosure 97x40 sold on eBay,
[eBay listing](http://www.ebay.com/itm/NO-STOCK-LimeSDR-enclosure-front-rear-panel-case-rtl-sdr-myriad-hackrf-airspy-/112088499793)
- 76x35 version samples ordered and hopefully arriving in 2 weeks (will try Dangerous Prototypes Fulfillment)
- receive packet from Lime Microsystems (they said they would send me defect board)

### ---> More in: [hardware/plug/1v2/Enclosure/](https://github.com/luftek/LimeSDR-USB/tree/master/hardware/plug/1v2/Enclosure/)


Sample of 97x40 design:

![Sample Enclosure 97x40](hardware/plug/1v2/Enclosure/0v3_Alu_Sample_better_documentation/_images/present_kit.jpg)


20160819_76x35_Combined_Bottom.png

![20160819_76x35_Combined_Bottom.png](hardware/plug/1v2/Enclosure/0v4_Alu_Sample_76x35/_images/20160819_76x35_Combined_Bottom.png)

20160819_76x35_Combined_Top.png

![20160819_76x35_Combined_Top.png](hardware/plug/1v2/Enclosure/0v4_Alu_Sample_76x35/_images/20160819_76x35_Combined_Top.png)

# LimeSDR

![LimeSDR board](/images/LimeSDR_722w.jpg)

The [LimeSDR](https://myriadrf.org/projects/limesdr/) board provides a hardware platform for developing and prototyping high-performance and logic-intensive digital and RF designs using Altera’s Cyclone IV FPGA and Lime Microsystems transceiver.

* **USB Interface** 
  * Cypress FX3 super speed USB 3rd generation controller 
* **FPGA Features**
  * Cyclone IV EP4CE40F23C8N device in 484-pin FPGA
  * 39’600 logic elements
  * 1134 Kbits embedded memory
  * 116 embedded 18x18 multipliers 
  * 4 PLLs 
* **FPGA Configuration**
  * JTAG mode configuration 
  * Active serial mode configuration 
  * Possibility to update FPGA gateware by using FX3 (USB)
* **Memory Devices** 
  * 2x 1Gbit (64M x 16) DDR2 SDRAM 
  * 4Mbit flash for FX3 firmware
  * 16Mbit flash for FPGA gateware
  * 3x 64K (8K x 8) EEPROMs for LMS MCU firmware, LMS MCU data and FX3 data
* **Connections**
  * 6-12V DC power jack
  * FPGA GPIO headers
  * Micro USB3.0 (type B) connector or USB3.0 (type A) plug
  * Coaxial RF (U.FL) connectors
* **Clock System**
  * 30.72MHz ±250 ppb on board VCTCXO
  * Possibility to lock VCTCXO to external clock or tune VCTCXO by onboard DAC 
  * Programmable clock generator for the FPGA reference clock input or LMS PLLs
* **Board Size** 60mm x 100mm (2.36” x 3.94”) 

## Contents

The directory structure is as follows:

      fx3/                       - Cypress FX3 USB 3.0 controller firmware
         
      gateware/                  - Altera Cyclone IV FPGA project

      hardware/<variant>/<version>/
          Libraries/             - Component Libraries
          OutputJobs/            - Output jobs
          PCB/                   - PCB design
          Project Outputs/       - BOM, rule check reports, Gerbers, pick & place files, PDFs
          Schematics/            - Schematic diagrams

## Licensing

### Hardware

The hardware designs are licensed under a Creative Commons Attribution 3.0 Unported licence.

### FPGA design

For details of the FPGA design licensing please see the associated COPYING file(s). However, please note that this does not extend to any files provided with the Altera design tools and see the relevant files for the associated terms and conditions.

### FX3 firmware

For details of the FX3 firmware licensing please see the associated COPYING file(s) and file headers.
