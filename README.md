# Reading Switch Inputs 

# Task
- Connect a 4-bit DIP switch and a pushbutton switch to the STM32. (The 4-bit switch represent a value from 0000 to 1111)
- Write a program to read in the DIP switch value (only) when the pushbutton switch is pressed
- The value 0000 on DIP switch should set the Knight Rider light to the slowest speed of about 1 second per LED (i.e. 6s second for 6 LEDs)
*** The value 1111  sets Knight Rider speed fastest, about 1 second from first to last (i.e. 1/6s per LED)
*** Any other value should represent the speed between slowest and fastest

# Group 2
- Zhang Zhen
- Tian Linxue
- Lim Zhi

# Steps
1) Connect all the hardware through jumper on a breadboard (DIP switche / push button are connected with pull up resistor)
2) Create a new project in STM32CudeIDE
3) Select the correct board (STM32F103C8)
4) Define the leds as output, DIP switch and push button as input in Pinout & Configuration
5) Modify code inside the while loop (core/src/main.c)
6) Read the state of DIP switch using HAL_GPIO_ReadPin() when only the push button is preseed
7) Based on the DIP switch value, display Knight Rider light with desired speed

# References
- https://uk.rs-online.com/web/content/discovery/ideas-and-advice/dip-switches-guide
