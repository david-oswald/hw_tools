# USB / Voltage breakout board

Provides a USB-to-UART interface using an FT230X. In addition, has a LM317
to provide a potentiometer-set output voltage. The IO voltage of the FT230X
can be jumper-configured to either use the voltage from the FTDI chip
(3.3 V, max. 50 mA) or the LM317 output (min. 100 mA, typ. 200 mA).
