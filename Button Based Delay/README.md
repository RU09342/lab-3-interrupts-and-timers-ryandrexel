# README for Button Based Delay

Ryan E. Drexel
	
	Created 05 October 2017
	Updated 09 October 2017

Embedded Systems- Dr. Tang and Mr. T.

Button Based Delay is a C language program designed to run on five MSP430 microprocessors (listed below)
	MSP430G2553
	MSP430FR6989
	MSP430F5529
	MSP430FR2311
	MSP430FR5994
Button Based Delay uses a bottun interrupt to change the frequency of a blinking button. Polling is used to blink the button itself,
and every time the button interrupt is triggered, the delay in the button blink is altered in order to change the blink frequency.
