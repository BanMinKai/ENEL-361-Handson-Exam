# ENEL-361-Handson-Exam
Data Analysis of Measurements from an ADC designed by students 

In this Handson Exam, we were required to design, implement and validate an Analog-to-Digital Converter (ADC)
  
    The designed ADC is under the category of Integrating ADC (specifically Single-Slope ADC). 
    The design is easy to implement because one part is an opamp-based integrator and an AVR-based timer
    
    The ADC is implemented using 2 opamps (MCP6002), and MOSFET (2N7000) and the timer is realized 
    by using an AVR microcontroller as an FPGA
    
    The validition process involves using a logic analyzer inside ADALM2000, 
    exporting a csv file and then processing that file using Python or Matlab
