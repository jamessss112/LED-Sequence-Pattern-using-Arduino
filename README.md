Variables Declaration
•	ledPins[]: An array that holds the pin numbers {12, 11, 10, 9, 8} where the LEDs are connected.
•	numLEDs: A variable that stores the total number of LEDs (5), making the code scalable if the number of LEDs changes.
Setup Function
•	The setup() function runs once when the program starts.
•	It initializes each pin in ledPins[] as an output using a loop.
•	The pinMode() function is used to configure each pin for output mode, allowing it to control an LED.
Loop Function
•	The loop() function runs continuously, creating a repeated LED pattern.
•	The process consists of two main phases:
Turning LEDs ON Sequentially
1.	A for loop iterates through the ledPins[] array.
2.	Each LED is turned ON using digitalWrite(ledPins[i], HIGH).
3.	A delay(1000); introduces a 1-second pause before lighting up the next LED.
Turning LEDs OFF Sequentially
1.	Another for loop iterates through the ledPins[] array.
2.	Each LED is turned OFF using digitalWrite(ledPins[i], LOW).
3.	Another delay(1000); ensures each LED stays off for 1 second before moving to the next.
Program Behavior
•	The LEDs turn on one by one, staying lit for 1 second each.
•	Once all LEDs are on, they turn off one by one in the same order, with the same 1-second delay.
•	This cycle repeats indefinitely, creating a simple LED sequencing effect.
This program is useful for understanding how to control multiple LEDs using an array and loops, making it a great starting point for more complex light sequences. 🚀

