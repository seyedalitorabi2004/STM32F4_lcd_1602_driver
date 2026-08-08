# STM32F4_lcd_1602_driver
This is a Library made for Using Character LCDs with STM32F4 MCU in mind. It uses ST HAL.\
Note that this is based off of Arduino's LiquidCrystal Library.\
\
the Example is made for STM32F401RCT6 (Black Pill) but you should be able to either reconfigure the project or copy the important part.\
\
Please note that in order for the delay_us to be usable, you should configure your timer, and the oscillator. this guide can be helpful. [Timer setup](https://controllerstech.com/create-microsecond-delay-stm32/)\
\
The main Code for the driver is in the lcd_1602_driver directory.\
Copy the header file to Core/Inc.\
Copy the c file to Core/Src.

Feel free to fork / Report issues.
