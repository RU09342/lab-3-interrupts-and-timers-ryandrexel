# README for Timer A Button

Ryan E. Drexel
	
	Created 05 October 2017
	Updated 09 October 2017

Embedded Systems- Dr. Tang and Mr. T.

Timer A Button is a C language program designed to run on five MSP430 microprocessors (listed below)
	MSP430G2553
	MSP430FR6989
	MSP430F5529
	MSP430FR2311
	MSP430FR5994
Timer a button turns an LED on for the amount of time equal to the amount of time a button is held down.
The pressing of a button triggers an inturrupt. Within the ISR, a counter begins. The ISR ends when the button
is released. When the interrupt is over, an if statement checks if the counter is greater than 0. While greater
than 0, the LED will be turned on and the counter will be decremented back down to 0.