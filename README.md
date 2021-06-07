# Thermostat_Task

![Capture](https://user-images.githubusercontent.com/85519031/121083383-02a5b680-c7fd-11eb-9dfc-ae2804ca0750.PNG)

Create a home thermostat with a potentiometer, LEDs (choose: 2 LEDs (red and blue), or one RGB), a temperature sensor, and an LCD (optional, can be replace with serial monitor).
1. LCD/Serial monitor greets users with a welcome message.
2. LCD/Serial Monitor displays the ambient temperature in deg.F in one line, and the set temperature (desired room temp) controlled by Pot on the next line. LCD refreshes every 5
seconds or less.
3. When the ambient tem<= (set temp-1), the red LED turns on and LCD/SM displays “heater
ON!”
4. When the ambient tem>= (set temp+1), blue LED turns on and LCD/SM displays “AC ON!”
5. Both LEDs cannot be on at the same time!
6. When the temperature is within ± 1deg.F of the set temperature, repeat step 2 and LEDs are OFF.
7. Create two separate custom functions for the heater and the AC.

  * Prepare an algorithm for the main script and your function.
  * You will need to use the codes provided to you from Sparkfun to create new code to run this program. All the attributes discussed above MUST function in one code file. 
  * Use constant variables to store pin numbers, tempPin, potPin, etc.
  * Your code should have enough comments to help me understand: What each line of your code does, and how the hardware is connected
  * Prepare a final wire diagram of the components used for this assignment using TinkerCAD!
