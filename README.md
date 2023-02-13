Task
---------
1) Connect a 4-bit DIP switch and a pushbutton switch to the STM32. (The 4-bit switch represent a value from 0000 to 1111)
2) Write a program to read in the DIP switch value (only) when the pushbutton switch is pressed
3) The value 0000 on DIP switch should set the Knight Rider light to the slowest speed of about 1 second per LED (i.e. 6s second for 6 LEDs)
*** The value 1111  sets Knight Rider speed fastest, about 1 second from first to last (i.e. 1/6s per LED)
*** Any other value should represent the speed between slowest and fastest

Group
---------
Zhang Zhen
Tian Linxue
Lim Zhi

Steps
---------
1) Create a new project in STM32CudeIDE
2) Select the correct board (STM32F103C8)
3) Define the leds as output and DIP switch as input
4) Add code inside the while loop (core/src/main.c)

References : https://uk.rs-online.com/web/content/discovery/ideas-and-advice/dip-switches-guide
