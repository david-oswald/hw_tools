# STM32F405 board in Raspberry Pi Zero form factor

STM32F405RGT6 (LQFP64) microcontroller board in the form factor of a RPi Zero. 

## Features

 - STM32F4xx MCU with 1 MB flash, 192 kB SRAM, USB 2.0, max. 168 MHz clock
 - Projects can use existing cases for RPi Zero
 - Programmable via bootloader (button) or programmer (SWD interface)
 - Powered from USB
 - Power LED + 2 user-defined LEDs
 - A few pins (not all) broken out to RPi connector
 - Power pins (GND, 3V3, *not* 5V) are assigned to correct RPi connector pins
 - Could be theoretically used as an add-on board for RPi zero, this is
   however *not* tested. Feel free to test and improve pin mapping.
 - 2 layer board, fairly standard / cheap components, most expensive part is
   [STM32F405RGT6](http://www.st.com/content/st_com/en/products/microcontrollers/stm32-32-bit-arm-cortex-mcus/stm32f4-series/stm32f405-415/stm32f405rg.html)
   at approx. 10 USD in small quantities
 - Easy to solder (LQFP, 0603 components)

## Mapped pins

 - PD2 -> GPIO17
 - PC12 -> GPIO18
 - PC10 -> GPIO22
 - PA15 -> GPIO23
 - PC11 -> GPIO27
 
## Todo
  
  - Provide example code
  - Pin mapping to work as RPi extension
  - Break out all remaining STM32F405 pins
   
