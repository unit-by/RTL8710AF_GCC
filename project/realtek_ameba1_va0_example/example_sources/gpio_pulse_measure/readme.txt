Example Description

This example describes how to use GPIO read/write mbed api to generate a pulse and to measure the pulse width.

Requirement Components:
    a wire

Pin name PC_4 and PC_5 map to GPIOC_4 and GPIOC_5:
 - PC_4 as the interrupt GPIO pin with no pull (High-Z).
 - PC_5 as output to generate a pulse.
 - Use a wire to connect PC_4 and PC_5

In this example, the UART consol will print out the measured width (in us) of the pulse which generated by PC_5.
